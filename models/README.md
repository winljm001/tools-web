# AI 模型文件

请将 LaMa 模型文件 `lama_fp32.onnx` 放置在此目录下。

## 模型下载

LaMa (Large Mask Inpainting) 模型可从以下地址获取：

- Hugging Face: https://huggingface.co/smartywu/big-lama
- 或者从官方仓库编译: https://github.com/advimman/lama

## 文件结构

```
public/models/
└── lama_fp32.onnx    # LaMa 模型文件 (~100MB)
```

## 注意事项

- 模型文件较大，首次加载可能需要几秒钟
- 模型使用 ONNX Runtime Web 在浏览器中运行
- 建议使用 FP32 版本以获得更好的效果
