# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  
  # https://docs.vagrantup.com.

  config.vm.box = "ximbled/ghost-box"

  config.vm.box_url = "https://dl.dropboxusercontent.com/u/204082701/package.box"

  config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.synced_folder "./ghost", "/var/www/ghost"

end

