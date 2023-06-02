FROM renien/spark-stand-alone-livy
RUN apt-get update
RUN pip3 install --upgrade pip
RUN pip3 install jupyterlab pyspark==2.4.7
#CMD ["jupyter", "lab", "--allow-root", "--ip=0.0.0.0", "--port=8888", "--no-browser"]