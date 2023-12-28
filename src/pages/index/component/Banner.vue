<template>
	<div>
		<h1>Banner</h1>
		<swiper
			class="swiper"
			circular
			:indicator-dots="indicatorDots"
			:autoplay="autoplay"
			:interval="interval"
			:duration="duration"
		>
			<swiper-item>
				<view class="swiper-item uni-bg-red">A</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item uni-bg-green">B</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item uni-bg-blue">C</view>
			</swiper-item>
		</swiper>
	</div>
</template>

<script setup>
const background = ['color1', 'color2', 'color3'];
const indicatorDots = true;
const autoplay = true;
const interval = 2000;
const duration = 500;
</script>

<style scoped>
	.uni-margin-wrap {
		width: 690rpx;
		width: 100%;
	}
	.swiper {
		height: 300rpx;
	}
	.swiper-item {
		display: block;
		height: 300rpx;
		line-height: 300rpx;
		text-align: center;
	}
	.swiper-list {
		margin-top: 40rpx;
		margin-bottom: 0;
	}
	.uni-common-mt {
		margin-top: 60rpx;
		position: relative;
	}
	.info {
		position: absolute;
		right: 20rpx;
	}
	.uni-padding-wrap {
		width: 550rpx;
		padding: 0 100rpx;
	}

</style>