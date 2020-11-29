# firwin designer using voila

This repository contains sample ipynb file(`firwin_designer.ipynb`) to test voila dashboard.

## how to run

The pyproject.toml in this repository requires python version above 3.8.

```sh
$ git clone https://github.com/wrist/voila_firwin_designer.git
$ cd voila_firwin_designer
$ poetry install
$ poetry run voila firwin_designer.ipynb
```

If you want to run voila app on jupyterlab, run below command.

```sh
$ poetry run jupyter labextension install @jupyter-voila/jupyterlab-preview
```
