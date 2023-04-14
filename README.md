
## Fundamental and Useful Tools and Tips for Data Science

## Python

### Useful to Start
#### Cheatsheet
  - [Python Basics Cheatsheet](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-hello-world/cheatsheet) by Codecademy

#### Short Course
  - [Scientific Computing with Python](https://www.freecodecamp.org/learn/scientific-computing-with-python/) by Freecodecamp

#### Blog
  - [How to get started coding in Python?](https://nbviewer.org/github/Tanu-N-Prabhu/Python/blob/master/How_to_get_started_coding_in_Python%3F.ipynb) by Tanu Nanda Prabhu
  - [The ipynb Jupyter Notebook File Extension](https://mljar.com/blog/jupyter-notebook-file-extension/#:~:text=ipynb%20file%20extension%20is%20used,computing%20in%20Python%20programming%20language.) by Piotr Płoński 
  - [How to Use Google Colab for Python](https://www.jcchouinard.com/google-colab-with-python/) by Jean Christophe Chouinard
  - [Write Python Clean Code Using These 3 Principles](https://levelup.gitconnected.com/learn-how-to-write-python-clean-code-using-these-3-principles-ed046978e39a) by Youssef Hosni
  - [20 Pandas Functions for 80% of your Data Science Tasks](https://levelup.gitconnected.com/20-pandas-functions-for-80-of-your-data-science-tasks-b610c8bfe63c) by Youssef Hosni
  - [How To Eliminate Loops From Your Python Code](https://levelup.gitconnected.com/how-to-eliminate-loops-from-your-python-code-6dfb7c3578fa) by Youssef Hosni
  - [Get your computer ready for machine learning: How, what and why you should use Anaconda, Miniconda and Conda](https://towardsdatascience.com/get-your-computer-ready-for-machine-learning-how-what-and-why-you-should-use-anaconda-miniconda-d213444f36d6) by Daniel Bourke

## Git and GitHub

### Markdown
#### Docs
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/#examples) 
#### Cheat Sheets
- [LaTeX Math Symbols Cheat Sheet](https://kapeli.com/cheat_sheets/LaTeX_Math_Symbols.docset/Contents/Resources/Documents/index)

### Git
#### Docs
- [Installation](https://git-scm.com/downloads)
- [Documentation](https://git-scm.com/doc)
- [Git Handbook (10 minute read)](https://guides.github.com/introduction/git-handbook/)
#### Cheat Sheets
- [Git Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
#### Videos and courses
- [Git](https://parsclick.net/course/PL3Y-E4YSE4wYFlcomsBtJy1nCu3jclA8L) by Amir Hasan Azimi (in Persian)

### Essential steps to set up your PC for graph machine learning with PyG

1. Install [miniconda3](https://docs.conda.io/en/latest/miniconda.html)

2. Create a [conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) as follows, and execute the following commands

    ```
    conda create -n gml python pip
    ```
    ```
    conda activate gml
    ```
    ```
    conda install ipykernel
    ```  
    ```
    python -m ipykernel install --user --name gml --display-name "Python (gml)"
    ```
    ```
    conda install -c conda-forge matplotlib scikit-learn pandas
    ```

4. Install [PyTorch](https://pytorch.org/get-started/previous-versions/)
    ```
    conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 cpuonly -c pytorch
    ```

5. Install NetworkX:
    ```
    conda install -c anaconda networkx
    ```

6. Install Scipy:
    ```
    conda install -c conda-forge scipy
    ```

7. Install PyG(Pytorch-Geometric):
    ```
    conda install -c pyg pyg
    ```

- Another options to install PyG:

  - Base on your python version: https://pytorch-geometric.readthedocs.io/en/latest/install/installation.html
  - For newer versions: https://pytorch-geometric.com/whl/
  - for older versions: https://data.pyg.org/whl/
  - An Installation example for version 1.9.0 of pytorch:
      ```
      pip install torch_scatter -f https://data.pyg.org/whl/torch-1.9.0%2Bcpu.html
      pip install torch_sparse -f https://data.pyg.org/whl/torch-1.9.0%2Bcpu.html
      pip install torch-geometric
      ```  

