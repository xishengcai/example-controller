### write your controller
this is one example

#### generate code
```gitexclude
cd $GOPATH/src
mkdir k8s.io && cd k8s.io
git clone https://blog.openshift.com/kubernetes-deep-dive-code-generation-customresources/
git clone https://github.com/xishengcai/example-controller.git
cd example-controller
./hack/update-codegen.sh
```

#### write your controller


#### build