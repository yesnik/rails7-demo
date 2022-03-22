# Rails 7 Demo

This project was created with the official Ruby on Rails [video tutorial](https://rubyonrails.org/).

## Requirements

1. Ensure that you have ruby installed:
  ```bash
  ruby -v
  # ruby 3.1.1p18 (2022-02-18 revision 53f5fc4236) [x86_64-linux]
  ```
2. Project uses PostgreSQL. Ensure that you have it:
  ```bash
  sudo service postgresql status
  ```

## Installation

1. Clone this repo:
  ```
  git clone git@github.com:yesnik/rails7-demo.git
  ```
2. Install dependencies:
  ```
  cd rails7-demo
  bundle install
  ```
3. Run setup command:
  ```
  rails db:setup
  ```
4. Run development server:
  ```
  rails server
  ```
