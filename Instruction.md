### create rails app
```sh
 rails new blog --api --database=postgresql
```

### bundle install
```sh
bundle config set --local path 'vendor/bundle'            

bundle install
```

### create database
```sh
bin/rails db:create
```

### add devise, jwt and cors
```sh
bundle add devise devise-jwt rack-cors
```

### install devise
```sh
rails g devise:install
```