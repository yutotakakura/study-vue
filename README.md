Dockerがインストールされていれば、下記の手順でローカルの8080番ポートで立ち上がります。
```
$ docker-compose build
$ docker-compose up -d
$ docker-compose exec app yarn serve
```