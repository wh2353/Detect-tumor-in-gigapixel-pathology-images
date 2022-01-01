# Detect tumor in gigapixel pathology images
<b>Columbia University Applied Deep Learning Course Project</b><br>
<b>Author:</b> Wenrui Huang<br>
<b>Date: </b> 2021-12-31<br>
## Motivation
- Each year, treatment decision of overall 230, 000 breast cancer patients in the US hinge on whether tumor has metastasized.
- Detection of metastasis is often a daunting task that involves well-trained pathologists reviewing an extensive amount of tissues.
- The whole human process is time-consuming and error prone and can only achieve ~73% sensitivty in tumor detection.
- <b>I thus propose a deep learning model that automates tumor detection in histological slides with a similar or better performance than human in order to facilitate clinical cancer diagnosis and treatment.</b><br> 
## Data
21 Gigapixal pathology image sets originate from [The CAMELYON16 CHALLENGE](https://camelyon16.grand-challenge.org/Data/) Dataset, in which each image set consists of a histological slide and corresponding mask that indiates tumor tissue, both in .tiff format. Each slide and mask contains seven zoom levels, in which 0 is the base zoom level and 7 is the highest.<br>
