# common_tips


## 1.To create an environment:

conda create --name myenv

## 2.To create an environment with a specific version of Python and multiple packages:

conda create -n myenv python=3.6 scipy=0.15.0 astroid babel

## 3.Create the environment from the environment.yml file:

conda env create -f environment.yml

## 4.Specifying a location for an environment

conda create --prefix ./envs jupyterlab=0.35 matplotlib=3.1 numpy=1.16

## 5.clone env

conda create --name new_name --clone old_name

## 6.remove env

conda remove --name old_name --all # or its alias: `conda env remove --name old_name`

## 7.check env

conda env list

## 8.activate env

conda activate myenv

## 9.deactivate env

conda deactivate myenv