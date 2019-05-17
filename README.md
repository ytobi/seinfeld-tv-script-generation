# Seinfeld TV scripts generation

In this project, I implemented a model to generate Seinfeld TV scripts using RNNs. The dataset was part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network generates new, "fake" TV script, based on patterns it recognizes in this training data.

# Installation

For best experience with managing dependency I advise you install [Anconda](https://docs.anaconda.com/anaconda/install/) or [miniconda](https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/download.html).

Create a virtual environment with conda
```
conda create --name deep-learning python=3
```
Activate environment.
```
source activate deep-learning
```

Install dependencies.

```
pip install -r requirements.txt
```

Download or clone this seinfeld-tv-script-generation repository. Launch the app with jupyter-notebook.
```
jupyter-notebook dlnd_tv_script_generation.ipynb
```

# Usage


### Run
Run all code cells in the notebook (This will take a while to run on a CPU as the code will construct and train a recurrent neural network, preferably you should run on a GPU).

You can already view a sample generated script in `generated_script_1.txt`.

Generated scripts closely resembles actual scripts from Seinfeld.




