# Air Quality Patterns in Durham County, 2018–2020

Exploratory analysis of daily CO, PM2.5, and ozone concentrations from the EPA air quality monitor at RDU airport, motivated by research on sickle cell disease (SCD).

## Data
`data/AQ_2018.csv`, `data/AQ_2019.csv`, and `data/AQ_2020.csv` are the provided EPA monitor extracts. 2020 covers January–April only.

## Structure
- `Project2.Rmd`: reproducible cleaning function, descriptive tables, and plots
- `Project2.docx`: formatted report (no code shown)
- `data/`: original annual CSV files
- `figures/`: exported report figures

## Reproduce
1. Install R and RStudio; install packages: `install.packages(c("dplyr","tidyr","ggplot2","readr","lubridate","knitr","rmarkdown"))`.
2. Open the project folder in RStudio, set the working directory to the project root, and knit `Project2.Rmd` to Word.
3. Review the knitted Word report. The author’s GitHub profile is https://github.com/xiaohan820-create.
4. To meet the repository requirement, create a project repository, upload the project files, and make at least two genuine commits during development. The ZIP alone does not establish those commits.

## Author
Xiaohan Sun — November 22, 2026
