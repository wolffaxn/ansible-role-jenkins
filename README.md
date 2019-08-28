# Ansible Role - Jenkins CI

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/wolffaxn/ansible-role-jenkins/master.svg)](https://github.com/wolffaxn/ansible-role-jenkins)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [About](#about)
- [Requirements](#requirements)
- [Role Variables](#role-variables)
- [Dependencies](#dependencies)
- [Example Playbook](#example-playbook)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## About

Installs Jenkins CI for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

tbd

## Dependencies

None.

## Example Playbook

For RHEL / CentOS

```yaml
---
- hosts: localhost
  remote_user: root
  roles:
    - ansible-role-jenkins
```

## License

This project is licensed under the terms of the [MIT license](LICENSE).
