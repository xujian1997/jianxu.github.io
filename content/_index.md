---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.svg
          filters:
            brightness: 0.3
            opacity: 0.1
            contrast: 0.3
            saturate: 0.2
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: my_research
    content:
      title: '🌏 My Research'
      subtitle: ''
      text: |-
        My research focuses on induced seismicity associated with hydraulic fracturing in the Changning shale gas field. I have successfully constructed a high-resolution shear wave velocity model using ambient noise tomography based on a dense array and developed a precise seismicity catalog for the study region. Leveraging these observations, I have analyzed the key factors controlling the maximum magnitudes of induced earthquakes, characterized two distinct seismogenic patterns, and assessed seismic hazards by integrating seismic observations with geomechanical modeling (COMSOL). Currently, I am working on in-situ Vp/Vs estimations to gain a deeper understanding of the activation processes of seismogenic faults that host induced earthquakes.
        
        In addition to my research on hydraulic fracturing-induced seismicity, I plan to expand my studies to other forms of induced seismicity caused by enhanced geothermal systems (EGS), wastewater disposal (WD), and CO₂ storage in my future career. My overarching research goal is to contribute to the mitigation of seismic hazards and risks associated with anthropogenic activities by elucidating the triggering mechanisms and source processes of induced earthquakes, particularly moderate to strong events.
        
        My technical skills include: (1) developing high-precision seismicity catalogs, from event detection to accurate (re)location; (2) characterizing georeservoir structures using ambient noise tomography; (3) conducting geomechanical modeling to simulate pore pressure diffusion and poroelastic stress perturbations induced by fluid injection; and (4) estimating in-situ Vp/Vs ratios using high waveform similarity techniques.
    design:
      columns: '1'
  - block: collection
    id: highlights
    content:
      title: Result highlights
      filters:
        folders:
          - features
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: True
    design:
      view: citation
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
