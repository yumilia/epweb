# web-rails-simple

Rails Sample Application

# Developer Workspace
[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/)

# Stack to use

FROM [codenvy/ubuntu_rails](https://hub.docker.com/r/codenvy/ubuntu_rails/)

# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Install dependencies | `cd ${current.project.path} && sudo bundle install` |
| 2      | Run | `cd ${current.project.path} && sudo rails server -b 0.0.0.0` |
