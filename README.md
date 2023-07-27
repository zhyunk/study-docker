# docker-test

### 1. docker login
```bash
docker login
```

### 2. docker build : Dockerfile 읽어서 이미지 생성
```bash
docker build -t zhyun/spring-boot .
```

### 3. docker repository upload
```bash
docker push zhyun/spring-boot
```

<br/>

언젠간 project build 부터 docker build 및 push 까지 github actions 로 해보는 꿈을 꿔봄 😬
