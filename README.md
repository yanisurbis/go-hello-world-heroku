# Hello World Heroku

- read this [article](https://signednull.com/starting-with-go-modules-on-heroku/)
- ```
  go build
  export PATH=$PATH:$(pwd)
  heroku local
  echo "web: go-hello-world-heroku" >> .env
  echo ".env" >> .gitignore
  heroku create go-hello-world-heroku
  git push heroku master
  heroku open
  ```