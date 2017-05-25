# Docker Image for ansible-playbook
i.e.
```
docker run --rm -it -v $(pwd):/ansible -v ~/ansible/vault:/ansible/vault ymuski/ansible-win_support -i InventoryFilePath playbook.yml --vault-password-file vault/pass
```

The playbook will be executed in the container which will be removed after that.

[usefull link ansible on alpine](http://mowson.org/karl/2016/2016-05-22_install_ansible_under_alpinelinux/)
