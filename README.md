# Link to deployed app

https://malaria-single-cell-detector.onrender.com [Not working anymore - free tier is done]

To use it:

- Clone repository to your computer

- Test locally by installing Docker and using the following command in the root of the directory:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
