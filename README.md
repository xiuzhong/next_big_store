# README

This README would normally document whatever steps are necessary to get the
application up and running.

- install Ruby
```
# follow this guide: https://github.com/rbenv/rbenv#installation
> brew install rbenv
> rbenv init
# Close you terminal and open a new one, so your changes take effect
> rbenv install 2.5.8
```

- install ImageMagick
```
> brew install imagemagick
```

- install next_big_store
```
> git clone https://github.com/xiuzhong/next_big_store.git
> cd next_big_store
> bundle install
> bundle exec rails s
```

That's all, the e-shop is ready on http://localhost:3000
The admin of e-shop is ready on http://localhost:3000/admin with:
  - username: spree@example.com
  - password: spree123
