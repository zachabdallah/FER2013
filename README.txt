'''
  to run this code on macOS:
step 1: make virtual environment for IDE (we used vscode)
    brew install python@3.10 #python 3.10 is what google collab uses
    python3.10 —version #verify correct version
    python3.10 -m venv tensorflow-env
    source tensorflow-env/bin/activate
  
make sure you’re scoped into your virtual environment now so that you’re installing the libriaries below in there. It should look like this: (tensorflow-env) zachabdallah@Zachs-MacBook-Air ~ % 

step 2: pip install notebook ipykernel (installs jupyter for .ipynb files)

step 3: python -m ipykernel install --user --name=tensorflow-env --display-name "Python (tensorflow-env)" (ensures .ipynv files in VScode can use the virtual environments python interpreter and librarires)

step 3: pip install tensorflow-macos tensorflow-metal 

step 4:  pip install matplotlib numpy scikit-learn

step 5: pip install Pillow

step 6: select the correct kernel in VScode and run project

  to download FER2013 dataset, go to https://www.kaggle.com/datasets/msambare/fer2013
  is is already in training and test sets with labeled facial expressions
'''
