# ForSer ASD Biomarker Classification Model

Testing Accuracy: 77%

This repo documents the renovation of a pre-existing machine learning model used to classify ASD based on measured protein serum levels in several subjects.

The data and previous model come from Hewitson *et al.* (2021). *Blood biomarker discovery for autism spectrum disorder: A proteomic analysis.* PLoS One. 2021 Feb 24;16(2):e0246581. doi: 10.1371/journal.pone.0246581. Data are publicly available and were accessed on September 19, 2024.

### Repository contents

-   `data` contains

    -   `biomarker-raw.csv` raw data as retrieved from PLoS One

    -   `biomarker-clean.RData` processed data

-   `scripts` contains

    -   `preprocessing.R` script used to generate the processed data

    -   `previous-analysis.R` concise version of code used to replicate published analysis

-   `results` contains
    - `report.qmd` QMD file with improved model code
    - `report.html` Rendered HTML Report

Authors: Ivan Li, Mai Uyen Huynh, Valerie De La Fuente, Reese Karo
