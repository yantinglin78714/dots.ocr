from vllm/vllm-openai:v0.9.1

# 優先安裝 packaging 這個前置套件，來解決 flash-attn 的安裝問題
RUN pip3 install packaging

# 接著再安裝原本的套件
RUN pip3 install flash_attn==2.8.0.post2
RUN pip3 install transformers==4.51.3
