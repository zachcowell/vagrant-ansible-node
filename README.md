# frontend-gulp-starter
Gulp starter template for frontend (BS3, jQuery, RiotJS)

## Getting Project Running Locally

* [Install Git](http://git-scm.com/book/en/Getting-Started-Installing-Git#Installing-on-Linux)

* [Install node.js](http://nodejs.org/)

    * At the time of creation node.js version is: 4.2.1
    * ***NOTE: DO NOT INSTALL NODE USING HOMEBREW*** - There are several known issues
      involving npm and homebrew.

* [Install bower](http://bower.io/)

        npm install -g bower

* [Install gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)

        npm install -g gulp

* Clone project locally

        HTTPS:  git clone https://github.com/zachcowell/frontend-gulp-starter.git

* Cd into project directory (frontend-gulp-starter)

        cd frontend-gulp-starter

* Enter the following command into the terminal at the project root to start.

        npm install && gulp

## Gulp Tasks

      ├─┬ default
      │ └── watch
      ├─┬ browserSync
      │ └── build
      ├── build
      ├── clean
      ├── extras
      ├── images
      ├── scripts
      ├── scss
      ├── html
      ├─┬ watch
      │ └── browserSync
      └── usemin
