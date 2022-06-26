# README

This README would normally document whatever steps are necessary to get the
application up and running.

# Notes to get project running

When we first created the application, webpacker was not installed correctly.

Here are the steps that we took:

- `bin/webpack-dev-server` to check the webpacker server (it was not working)
- Moved dependencies out of `devDependencies` in `package.json` into the regular `dependencies` [link to github comment](https://github.com/rails/webpacker/issues/1178#issuecomment-372956197)
- We had to explicitly add `@rails/webpacker` into the `package.json` file
- Then we tried the `bin/webpack-dev-server` command again, and it said that it could not resolve `babel-loader` so we manually installed it with `npm install babel-loader`
- Finally we tried to verify the webpacker server once more and it was working, with some complaints (par for the course, JavaScript)



Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
