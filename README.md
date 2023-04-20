build react 18.1.0 with sourcemap linking to src code 

# how to use 

## prepare
There are 2 ways:

**use the prebuilt**

```
1. cd  build/node_modules/react && npm link
2. cd  build/node_modules/react-dom && npm link
```

**rebuid the sourcecode**

```
1. npm i && npm build
2. cd  build/node_modules/react && npm link
3. cd  build/node_modules/react-dom && npm link
```

## link your app source code

**demo for fun**

```
cd demo 
npm install 
npm link ract@18.1.0
npm link ract-dom@18.1.0
npm run start
```

and you are good to go .

![image-20230420220351112](https://md4zk.oss-cn-beijing.aliyuncs.com/uPic/image-20230420220351112.png)


**debug your own project**

in your react app project, switch to `react 18.1.0` and link the external source code

```
npm link ract@18.1.0
npm link ract-dom@18.1.0
npm run start
```






