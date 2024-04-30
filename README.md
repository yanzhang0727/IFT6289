# Tool Use And LLM Agents

In this project, we have done some experiments on how to make Llama 2-7B using tools and work with external documents to eliminate hallucination and give better information.

## Code 
The whole experiments are run on Google Colab using T4 or V100 GPU, the python version is `3.10.12`, to run the code, it just needs to run each grill in the notebook in order, note that it requires to restart the session after installing all packages in Colab due to some version conflicts of certain libraries. \
However, if you want to run the code locally, the necessary libraries are included in `requirements.txt`,it's also possible to use either Conda or Virtualenv to work with the environment. 

To directly install required packages:
```
python-m pip install-r requirements.txt
```

To generate one with your own environment:
```
pip freeze > requirements.txt
```

## Notebooks
All notebooks of our experiments can be find in `\Codebase\` folder, and the data used are in `\DATA\`