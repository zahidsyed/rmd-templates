# Intent
This planned collection of Rmd templates will be incorporated into my [TDSP-based CCDS project structure](https://github.com/zahidsyed/ccds-py-r). 

The intent is to 
- Have different .Rmd template files for use in the notebooks folders (data_acq, data_prep, model_dev and model_deploy) with appropriate template headings present in them. 
- The knitted HTML/PDF will also be directed into an appropriate subfolder when using the render command.

# Installing the Templates

If you want to trial these templates within R Markdown, you can install the templates directly:

````
install.packages("devtools")
devtools::install_github("zahidsyed/rmd-templates")
````

# Inspiration
Based off [Harper's templates](https://github.com/dr-harper/example-rmd-templates)