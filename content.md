layout: true
  
<div class="my-header"></div>

<div class="my-footer">
  <table>
    <tr>
      <td style="text-align:right">Saxon State and University Library Dresden</td>
      <td></td>
      <td style="text-align:right"><a href="https://www.slub-dresden.de/">www.slub-dresden.de</a></td>
    </tr>
    <tr>
      <td style="text-align:right">OpenITI WS</td>
      <td>2020-01-29</td>
    </tr>
  </table>
</div>

<div class="my-title-footer">
  <table>
    <tr>
      <td style="text-align:left"><b>Kay-Michael Würzner</b></td>
    </tr>
    <tr>
      <td style="text-align:left">Research Software Engineer</td>
    </tr>
    <tr>
      <td style="font-size:8pt"><b>2020-01-29</b></td>
    </tr>
    <tr>
      <td style="font-size:8pt">Open Islamicate Texts Initiative Workshop</td>
    </tr>
  </table>
</div>

---

class: title-slide
count: false

# Multi-source OCR workflows with OCR-D
## Building blocks for superior digital text

---

# Overview

- OCR-D: The project and its philosophy
- `ocrd`: The toolkit and its design
- Outlook and collaboration options

---

class: part-slide
count: false

# The project

---

# OCR-D: The project

- DFG-organized expert Workshop *Verfahren zur Verbesserung von OCR-Ergebnissen* (2014):
  > A concerted effort for improving OCR is required!
- Large-scale funding initiative
    + Targeting the *Verzeichnisse der im deutschen Sprachraum erschienenen Drucke* (VDs)
        * List of **all printed publications** issued in the German language area
        * Sorted by centuries (VD16, VD17, VD18)
        * (Image digitization completed)
    + Coordinated and prepared by OCR-D
        * Herzog August Library Wolfenbüttel
        * Berlin State Library
        * Berlin-Brandenburg Academy of Sciences and Humanities
        * Karlsruhe Institute of Technology

---

# OCR-D: Timeline

- Stage 1 (2015--2017)
    + Identification of requirements
    + Setting up a call for participation
    + Planning a technical framework
![Functional Model](img/functional_model.png)

---

# OCR-D: Timeline

- Stage 2 (2018--2020)
    + Implementing the technical framework
    + (Quasi-)Simultaneous operation of **eight module projects**
        * **Image optimization**: German Research Centre for Artificial Intelligence
        * **Layout analysis**: German Research Centre for Artificial Intelligence; University of Würzburg
        * **OCR Post correction**: University of Leipzig; Ludwig Maximilian University of Munich
        * **Font identification and OCR training**: Johannes Gutenberg University Mainz with Friedrich–Alexander University Erlangen–Nürnberg and University of Leipzig
        * **Improving Tesseract**: Mannheim University Library
        * **Long-term archiving**: Göttingen State and University Library
    + Early adoption in **nine different libraries**
        * Libraries of the coordination project partners
        * University and State Library Darmstadt
        * University and State Library Halle
        * Göttingen State and University Library
        * Mannheim University Library
        * Heidelberg University Library
        * Saxon State and University Library Dresden

---

# OCR-D: Timeline

- Hiatus (Final workshop in Bonn, 2020-02-12)
- Stage 3 (2020--2023, if approved)
    + Instanciation of the OCR-D software in libraries and archives
    + Development of usage models
        * Commercial providers of digitization services?
        * “Central” (public) digitization services?
        * Local infrastructure in each facility
    + Development of productive workflows
        * Optimized tool chains for specific materials
        * OCR and OLR models
- Stage 4 (???)
    + Going productive, i.e. mass digitization of the VDs under comparable conditions
        
---

class: part-slide
count: false

# The toolkit

---

# `ocrd`: The toolkit

- Key concepts:
    * **Operation**: Step in an OCR workflow
    * **Processor**: Program which performs an operation
    * **Module**: Collection of processors
    * **Workspace**: 
- Collection of repositories: [github.com/OCR-D](https://github.com/OCR-D)
    1. Specifications
        + Formats
        + Interfaces
    2. API/CLI
        + Python- and BASH-based
        + Exposing formats and interfaces
        + Provides common utility functions (e.g. image rotation and cutting)
    3. Sample processors
        + Wrappers to OCR-related tools
- Developed and maintained by OCR-D

---

# 

---

class: part-slide
count: false

# Outlook and collaboration options

---

class: part-slide

# Many thanks for your attention!

<center>
<a href="https://wrznr.github.io/OpenITI-2020/">wrznr.github.io/OpenITI-2020</a>
</center>
