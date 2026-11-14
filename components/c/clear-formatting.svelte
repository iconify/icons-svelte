<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in1_3hbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clear-formatting" {...props}></Icon>
<style>
:global(.in1_3hbmq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5H15m-5.75 0v15m6.25-4l5 5m0-5l-5 5");
}

</style>
