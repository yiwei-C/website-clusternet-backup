---
title: Clusternet Homepage
description: Hugo zzo, zdoc theme documentation home page
date: 2020-01-26T04:15:05+09:00
draft: false

landing:
  height: 500
  image: logo/Clusternet_blue_horizontal.png
  title:
    - Clusternet
  text:
    - Managing your Kubernetes clusters (including public, private, edge, etc) as easily as visiting the Internet ⎈
  titleColor:
  textColor:
  spaceBetweenTitleText: 25
  buttons:
    - link: docs
      text: Learn More
      color: primary
    - link: https://github.com/clusternet/clusternet
      text: Download
      color: default
      logo: logo/Clusternet_blue_horizontal.png
  backgroundImage:
    # src: https://cdn.pixabay.com/photo/2012/01/09/09/59/earth-11595_960_720.jpg
    # src: https://cdn.pixabay.com/photo/2018/12/10/10/21/earth-3866609_960_720.jpg
    src: https://cdn.pixabay.com/photo/2018/04/28/16/40/network-3357642_960_720.jpg
    height: 600
    ## To support background color,       <div style="background-color: #FF0000; background-position: center; background-repeat: no-repeat; background-size: cover; position: absolute; top: -50px; left: 0; width: 100%; height: {{ .height }}px;"></div>

footer:
  sections:
    - title: General
      links:
        - title: Docs
          link: https://gohugo.io/
        - title: Releases
          link: https://gohugo.io/
        - title: Blog
          link: https://gohugo.io/
    - title: Resources
      links:
        - title: GitHub
          link: https://github.com/clusternet/clusternet
        - title: Helm Charts
          link: https://github.com/clusternet/charts
        - title: Command Line Tool (kubectl-clusternet)
          link: https://github.com/clusternet/kubectl-clusternet
    - title: Contacts
      links:
        - title: GitHub Issues
          link: https://github.com/clusternet/clusternet/issues/new/choose
        - title: Google Group
          link: https://groups.google.com/g/clusternet
        # - title: Slack
        #   link: https://gohugo.io/
  contents:
    align: left
    applySinglePageCss: false
    markdown:
      |
      ## Clusternet
      Copyright 2021 The Clusternet Authors & ©THL A29 Limited, a Tencent company. All Rights Reserved. [LICENSE](https://github.com/clusternet/clusternet/blob/main/LICENSE)

sections:
  - bgcolor: teal
    type: card
    description: "An open-source project that helps users manage multiple Kubernetes clusters as easily as 'visiting the Internet' (thus the name 'Clusternet'). It is a general-purpose system for controlling Kubernetes clusters across different environments as if they were running locally."
    header:
      title: What is Clusternet
      hlcolor: "#8bc34a"
      color: '#fff'
      fontSize: 32
      width: 320
    rows:
      - description: row 1
        cards:
          - subtitle: Kubernetes Native
            subtitlePosition: center
            description: "Out-of-the-box Kubernetes add-on to empower multi-cluster management and application orchestration."
            image: images/section/keyboard.png
            color: white
          - subtitle: Application Management
            subtitlePosition: center
            description: "Two-tier application configuration to define generic and cluster-specific overrides. Priority setting is also offered for dynamic override chains."
            image: images/section/processor.png
            color: white
          - subtitle: Catered for all cloud categories
            subtitlePosition: center
            description: "Manages Kubernetes clusters across public, private, hybrid, and edge clouds from a single management cluster."
            image: images/section/root-server.png
            color: white
      - description: row 2
        cards:
          - subtitle: RBAC Support
            subtitlePosition: center
            description: "Support accessing all managed clusters with RBAC."
            image: images/section/root-server.png
            color: white
          - subtitle: CLI Support
            subtitlePosition: center
            description: "Control using plugin installable via [Krew](https://github.com/kubernetes-sigs/krew)"
            image: images/section/root-server.png
            color: white
          - subtitle: Placeholder
            subtitlePosition: center
            description: "Placeholder"
            image: images/section/root-server.png
            color: white

  - bgcolor: DarkSlateBlue
    type: card
    description: "placeholder"
    header:
      title: Join Us
      hlcolor: DarkKhaki
      color: "#fff"
      fontSize: 32
      width: 130
    rows:
      - description: row 1
        cards:
          - subtitle: Join community forum
            subtitlePosition: center
            description: "Follow [Clusternet Google Group](https://groups.google.com/g/clusternet) for announcements and technical Discussions."
            image: images/section/keyboard.png
            color: white
          - subtitle: Contributing
            subtitlePosition: center
            description: "Create a [Pull Request](https://github.com/clusternet/clusternet/pulls) on GitHub to get started.
New users are always welcome!"
            image: images/section/processor.png
            color: white
          - subtitle: Reporting Issues
            subtitlePosition: center
            description: "If you encounter any issues, feel free to open an [issue](https://github.com/clusternet/clusternet/issues/new/choose)."
            image: images/section/processor.png
            color: white

          # - subtitle: Join us on Slack
          #   subtitlePosition: center
          #   description: "Join [Clusternet Slack]() for live conversation and quick questions."
          #   image: images/section/root-server.png
          #   color: white

---
