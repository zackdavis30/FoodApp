# README
AWS 

ssh -i (Path_to .pem) ec2-user@(Public IP)

installing packages:

// updates everything: 

sudo yum update -y 

//get git hub installed: 

sudo yum install git-all

//show git installed: 

which git

//get packets:

git clone (github clone url goes here)

// C complier

sudo yum install gcc

//RVM **go to https://rvm.io/**

gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

\curl -sSL https://get.rvm.io | bash -s stable

source /home/ec2-user/.rvm/scripts/rvm

//update RVM 

rvm get head

// install ruby 

rvm install ruby-2.3.1

// install gem

gem update --system 

// install rails 

gem install rails -- no-document

// install Node.js

sudo yum install -y epel-release

sudo yum install -y --enablerepo=epel nodejs npm

**** IN APP FOLDER ****

// install new bundler in app folder 

bundler install 

// updates

bin/rails db:migrate RAILS_ENV=development

// starting puma 

rails server -b 0.0.0.0

// make some adjustments in routes.rb

roots 'foods#index' // then set it using >>> bins/rails routes


Notes:

ls -laF

Links:
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/ruby-development-environment.html
https://www.youtube.com/watch?v=jFBbcleSPoY
https://rvm.io/
https://www.phusionpassenger.com/library/walkthroughs/deploy/ruby/aws/nginx/oss/install_language_runtime.html


* ...
# FoodApp
