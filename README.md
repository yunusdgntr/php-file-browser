# File browser php with docker.

```
$ git clone https://github.com/yunusdgntr/php-file-browser
$ cd php-file-browser
```

```
$ sudo docker build -t filebrowser .
```

```
$ sudo docker run -d -p 80:80 --name my-file-browser filebrowser
```
![alt text](https://raw.githubusercontent.com/yunusdgntr/php-file-browser/master/screen.jpg)