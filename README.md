# Cookiecutter Project Template

Adapted from the [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) template.


_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._



### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project:
------------
cd to path where the project should be created locally and run:

    cookiecutter https://github.com/wiesehahn/cookiecutter-data-science



### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```

    ├── README.md          <- The top-level README with project information.
    |
    ├── code               <- Source code for use in this project.
    │   ├── analysis       <- e.g. Code to generate reports 
    │   ├── data           <- Scripts to download, generate or process data.
    │   ├── exploratory    <- Exploratory code and scipts in progress.
    │   ├── functions      <- Reusable code such as functions.
    │   └── viz            <- Scripts to create exploratory and results oriented visualizations.
    |
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   └── processed      <- The final data sets for modeling or analysis.
    │
    ├── docs               <- `index.md` or `index.html` to render at your GitHub Pages URL is stored here.
    │
    ├── resources          <- Figures, literature, manuals, and all other explanatory materials.
    │   ├── documents      <- External documents such as project outlines. 
    │   └── figures        <- External figures used in reports such as logos.
    │
    ├── results            <- Results as part of this project.
    │   ├── figures        <- Generated graphics and figures to be used in reporting 
    │   └── reports        <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    ├── templates          <- Template scripts, documents etc.
    |
    ├── LICENSE            <- License file for the project (optional)
    |
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt` (optional)

```
