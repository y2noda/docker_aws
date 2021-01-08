# docker_aws

$ docker run -itd  -v `pwd`:/kaggle -p 8888:22 -d --name kaggle_ssh --memory-reservation=12g --restart=always --gpus all my_docker_kaggle
