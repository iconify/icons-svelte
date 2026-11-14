<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh1wnvb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-clip" {...props}></Icon>
<style>
:global(.zh1wnvb1t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4H3v16h2M19 4h2v16h-2M7 12l2-4l2 8l2-10l2 12l2-6");
}

</style>
