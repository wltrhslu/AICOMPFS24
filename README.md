# AICOMP FS24

## 1 - Introduction

This is a repository for the FS24 AI competition module. In this module, we will be competing in the [PlantTraits2024 - FGVC11](https://www.kaggle.com/competitions/planttraits2024/overview).

## 2 - Installation

First, clone the repository:

```bash
git clone
```

This project uses a devcontainer for development in VSCode. To use it, you need to have [Docker](https://www.docker.com/) and the devcontainer extension installed. Once you have Docker installed, you can open this project in VSCode and you will be prompted to open the project in a devcontainer. This will build the devcontainer, install all dependencies and open the project in a container.  

Otherwise, you can install the dependencies locally. To do this, you can run the following command:

```bash
pip install -r requirements.txt
```

## 3 - Data

The data for this competition is available on the [competition page](https://www.kaggle.com/competitions/planttraits2024/data). You will need to download the data and place it in the `data` directory.

## 4 - Code
All notebooks are in the `code` directory. To reproduce our results, you can run the notebooks in the following order:
- `01_dqa_image.ipynb`
- `02_dqa_tabdata.ipynb`
- `05_multi-modal-model.ipynb`

`03_baselines.ipynb` contains the code for the baselines we used. `04_image_model.ipynb` contains the code for the first experiments with `Pl@ntNet`.