---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: experience
  content:
    date_format: Feb 2023
    items:
    - company: Societe Generale
      company_logo: sg-logo
      company_url: ""
      date_end: ""
      date_start: "2023-02-13"
      description: |2-

          * During this internship, I had the opportunity to work within a team of highly skilled data experts dedicated to supporting the banking business lines . My main responsibilities revolved around leveraging the power of AI models to enhance the data quality within the third parties' dataset by detecting potential anomalies and suggesting appropriate data .
          * Moreover, I held the responsibility of co-following the complex extraction request book by querying in the data lake and also ensuring the results to be aligned with the users' requirements .

      location: Île-de-France, France
      title: Group referentials data scientist 
    - company: Orika retail software
      company_logo: orika-logo
      company_url: ""
      date_end: "2022-09-10"
      date_start: "2022-05-20"
      description: |2-

          * Throughout my internship at Orika, I was involved in three distinct projects: the development of a mobile app for product recognition called o4iz, the creation of a console-based cash register system called tuipos, and the development of a web application for activity reports .
      location: Lyon, France
      title: Full Stack web and mobile developer 
    - company: LIG - Grenoble Informatics Laboratory
      company_logo: lig-logo
      company_url: ""
      date_end: "2022-04-20"
      date_start: "2022-02-20"
      description: |2-

          * In this project, we create more sophisticated fake scientific research papers by combining a neural network-based text generator (LSTM) with a grammar-based text generator. The goal is to challenge existing detectors and develop a more robust detection method..
      location: Grenoble, France
      title: Research project in Natural Language Processing
    title: Experience
  design:
    columns: "2"

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: AI projects
      tag: AI projects
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects

- block: contact
  content:
    address:
      city: Paris
      country: France
      country_code: Fr
      postcode: "75009"
      region: 
      street: 59 Rue Saint lazare 
    appointment_url: 
    autolink: true
    contact_links:
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    directions: 
    email: zinebettarraf@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    phone: +33 664966150
    subtitle: null
    text: Please do not hesitate to reach out to me if you are interested in further communication.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
