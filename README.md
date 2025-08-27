# Docker-Image
用于构建docker镜像，github action配置文件

## 配置一: docker-image.yml

* 构建镜像并向 GitHub Container Registry（ghcr.io）推送，只需修改配置文件里面的镜像名为你的 `github用户名/仓库名` 

## 配置二: docker-hub-image.yml

* 构建镜像并向 docker hub 推送，需要`修改配置文件`和`添加环境变量`

* 修改配置文件里面的镜像名为你的 `docker用户名/仓库名` 

* 设置环境变量，打开 `settings->secrets and variables->actions` ，选择 `secrets` 
  
* 变量名 `DOCKERHUB_USERNAME` 你的docker hub的用户名
  
* 变量名 `DOCKERHUB_TOKEN` 你的docker hub令牌秘钥（不是密码）
  
