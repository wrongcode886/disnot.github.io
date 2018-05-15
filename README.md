### 基本游戏架构
``` javascript
let onestroke = new OneStroke(
	{
		// 默认的线段颜色与端点颜色
		lineColor: 0xe2e2e2, 
		vertexColor: 0x6dc6c0, 
		strokeColor: 0x416275, 
		activeVertexColor: 0x6dc6c0, 
		levels: [
			{
				name: "第一关", 
				lineColor: 0xe2e2e2, 
				vertexColor: 0x90b34f, 
				strokeColor: 0x445624, 
				activeVertexColor: 0x90b34f, 
				lines: [
					{"x1": 375, "y1": 366, "x2": 200, "y2": 916},
					{"x1": 200, "y1": 916, "x2": 664, "y2": 576}, 
					{"x1": 664, "y1": 576, "x2": 88, "y2": 576}, 
					{"x1": 88, "y1": 576, "x2": 556, "y2": 916}, 
					{"x1": 556, "y1": 916, "x2": 375, "y2": 366}
				]
			}
		]
	}
);
```
