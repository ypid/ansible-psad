## psad

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Ansible Galaxy](http://img.shields.io/badge/galaxy-ypid.psad-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/3980)
[![Platforms](http://img.shields.io/badge/platforms-debian-lightgrey.svg?style=flat)](https://galaxy.ansible.com/detail#/role/3980)
[![GitHub Tags](https://img.shields.io/github/tag/ypid/ansible-psad.svg)](https://github.com/ypid/ansible-psad)
[![GitHub Stars](https://img.shields.io/github/stars/ypid/ansible-psad.svg)](https://github.com/ypid/ansible-psad)

### Warning, this is a BETA role

This role has been marked by the author as a beta role, which means that it
might be significantly changed in the future. Be careful while using this role
in a production environment.

***


### Installation

This role requires at least Ansible `v1.3`. To install it, run:

```Shell
ansible-galaxy install ypid.psad
```

To install via git, run either:

```Shell
git clone https://github.com/ypid/ansible-service_psad.git ypid.psad
git submodule add https://github.com/ypid/ansible-service_psad.git ypid.psad
```


### Role dependencies

- `debops.ferm`

### Role variables

List of default variables available in the inventory:

```YAML
---

service_psad_auto_dl:
service_psad_auto_dl_group:
service_psad_auto_dl_host:

service_psad_config:
  ENABLE_AUTO_IDS: N
  DISK_MAX_PERCENTAGE: 80
```




### Authors and license

`psad` role was written by:

- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)

License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
