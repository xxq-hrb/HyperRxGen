# HPG

This repository is the implementation of HPG. It includes two models: HGN-PG and HM-PG.

# HGN-PG:

## Required packages

torch == 1.5.0+cu101

torch-geometric == 1.4.3 

numpy == 1.18.1

pandas == 1.0.1

scikit-learn == 0.22.1

## Usage

train and test 

```python train_HGN_PG.py```

# HM-PG:

## Required packages

torch == 1.5.0+cu101

torch-geometric == 1.4.3

numpy == 1.22.1

pandas == 1.0.1

scikit-learn == 0.22.1

## Usage

train and test 

```python train_HM_PG.py```

predict

```python predict.py --predict --model_path "saved/HM_PG/final.model"```



