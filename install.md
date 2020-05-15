### 安装步骤
1. 安装gcc
``` bash
yum install gcc
```

2. 获取redis,下载redis6.0 make报错，，，安装5.0 就没报错， [官网](https://redis.io/download)
```
wget http://download.redis.io/releases/redis-5.0.8.tar.gz
```

3. 安装
``` bash
cd redis-5.0.8
make
make install
```

4. 使用
``` bash
cd src
./redis-server
```
