## ACS Melbourne 2022 workshop
https://cytometryconference.org.au/

R Materials for ACS Melbourne 2022 
Analytical Workflows for Single-Cell Multiomic Data workshop

## Date
Sunday, Nov 20, 9am

## Host
Wenyan Li

## Software required
Rstudio (free version) - download and install with this link:
https://posit.co/products/open-source/rstudio/

R - download and install the latest version. (Note: choose the one that matches your PC system)
https://cran.csiro.au/

## (encourage to try) Install R packages in Rstudio:
1. Open Rstudio
2. Inside the "Console", where you should see a welcoming message from R, showing what version of R you are using
3. type in the following line and hit enter. What this commend line does is install the Seurat package if you haven't installed it already
##### if (!require(Seurat)) install.packages("Seurat")
4. install package tidyverse
##### if (!require(tidyverse)) install.packages("tidyverse")
5. install package patchwork
##### if (!require(patchwork)) install.packages("patchwork")

## Download demo data
1. BD Rhapsody demo data
https://scomix.bd.com/hc/en-us/articles/360034192672-Rhapsody-WTA-Demo-Datasets
* download "WTA + Sample Multiplexing + AbSeq" from the list

2. 10X demo data
https://www.10xgenomics.com/resources/datasets/1-k-pbm-cs-from-a-healthy-donor-gene-expression-and-cell-surface-protein-3-standard-3-0-0
* files needed: Feature / cell matrix (filtered)
