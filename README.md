# packer_centos

centos image for ec2 and virtualbox.

## Version

- centos-6.5-x86_64-minimal-aws
- centos-6.6-x86_64-minimal-virtualbox
- centos-7.0-1406-x86_64-minimal-virtualbox

## How to use

```
# ec2
% export AWS_ACCESS_KEY_ID="..."
% export AWS_SECRET_ACCESS_KEY="..."
% packer build -only=centos-6.5-x86_64-minimal-aws box.json

# virtualbox
% packer build -only=centos-6.6-x86_64-minimal-virtualbox box.json

# all
% packer build box.json
```

## License

Copyright &copy; 2015 yukihir0
