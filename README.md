# Trajectory Inference Review Notebooks

This repository stores Jupyter Notebooks associated with the review article "Trajectory inference for single cell omics" by Hutton & Meyer.
Two analyses of the same dataset are performed; one using [Scanpy](https://scanpy.readthedocs.io)'s [PAGA](https://doi.org/10.1186/s13059-019-1663-x) and the other with [Monocle 3](https://doi.org/10.1038/s41586-019-0969-x).
Both approaches obtain comparable results for possible trajectories and estimates of pseudotime.

# Installation
To make a local copy of these notebooks, use the following command:  
> `git clone https://github.com/xomicsdatascience/trajectory_review`
  
or click the green "Code" button and download the .zip file directly. Before proceeding, we recommend using a virtual environment to execute the notebook.  
To run the PAGA notebook, you'll need to have Jupyter Notebook installed, along with the requirements listed in `requirements.txt`. You can install of these by running 
> `python3 -m pip install requirements.txt` # for Linux and Mac,

> `py -m pip install requirements.txt`  # for Windows machines.

The Monocle notebook requires Jupyter Notebook to be installed, along with the IRkernel to allow Jupyter to use R. Package dependencies are installed at the start of the notebook. Due to difficulties associated with the various R package versions and system libraries, the notebook has only been successfully execute on Windows machines.

# Issues
Don't hesitate to report any issues with the notebooks in this repository; if you're experiencing a problem, it's likely that others are, too, and we can only fix the problems we know about.
