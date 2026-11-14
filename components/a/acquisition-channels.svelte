<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmc62e0ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:acquisition-channels" {...props}></Icon>
<style>
:global(.zmc62e0ss) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19v-6M7 19V5m3.5 14V9m3-4l4.5 5.5h3M13.5 19l4.5-5.5h3");
}

</style>
