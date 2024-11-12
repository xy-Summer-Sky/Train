# 配置如下，依次执行即可

```

conda create -n train39 python=3.9

conda activate train39

pip install jupyter
pip install ipykernel


apt-get install vim

jupyter notebook --generate-config

vim ~/.jupyter/jupyter_notebook_config.py


直接顶部添加以下内容，允许远程访问
c.NotebookApp.ip = '*'
c.NotebookApp.open_browser = False
c.NotebookApp.port = 8888

jupyter notebook --allow-root

出现以下信息


pip install langchain==0.3.3
pip install langchain_community==0.3.2
pip install langchain_core==0.3.15
pip install faiss-gpu==1.7.2
pip install rank_bm25==0.2.2

pip install sentence-transformers

git lfs install

git clone https://www.modelscope.cn/AI-ModelScope/bge-large-zh-v1.5.git

pip install modelscope

pip install pandas

pip install IPython

git clone https://www.modelscope.cn/Xorbits/bge-reranker-large.git

pip install jieba
```