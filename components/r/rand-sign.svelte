<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzju-1lon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rand-sign" {...props}></Icon>
<style>
:global(.qzju-1lon) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20V4m0 0h5.5a4.25 4.25 0 0 1 0 8.5H7m4.5 0L17 20");
}

</style>
