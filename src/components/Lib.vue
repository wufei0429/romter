<template>
	<div class="container">
			<div class="side-bar">
				<router-link to="/tiku">题库</router-link>
				<router-link to="/ziyuan">资源库</router-link>
				<router-link to="/huodong">活动库</router-link>
			</div>
			<div class="content"><router-view /></div>
		</div>
	</template>
	
	<script>
	export default {
		name: 'Lib',
		data() {
			return {};
		}
	};
	</script>
	
	<style scoped>
	.container {
		display: flex;
		width: 90%;
		margin: 0 auto;
		
	}
	.side-bar {
		flex: 1 1 20%;
		display: flex;
		flex-direction: column;
		background-color: #fff;
		margin-top: 20px;
	}
	a{
		margin-bottom: 30px;
	}
	.content{
		flex: 1 1 80%;
		text-align: left;
		background-color: #fff;
		margin-left: 20px;
		padding-bottom: 20px;
	}
	</style>
