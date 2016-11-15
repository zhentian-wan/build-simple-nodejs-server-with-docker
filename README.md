# run

### build image
docker build -t myserver .

### check image exists
docker images

### docker run 
docker run -p 8000:8000 myserver