<template>
	<div class="wrap">
		<h3>单文件组件</h3>
		<p>{{msg}}</p>
	</div>
</template>

<script>
export default {
	data() {
		return {
			msg: 'hello world'
		}
	}
}
</script>

<style lang="less" scoped>
.wrap {
	border: 1px solid;
	height: 100px;
	h3 {
		color: red;
	}
	p {
		background: gray;
	}
}
</style>
