<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odo1bto5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pill-cutter" {...props}></Icon>
<style>
:global(.odo1bto5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.25a6.75 6.75 0 0 0 0 13.5Zm5.5 0a6.75 6.75 0 0 1 0 13.5ZM12 2.5v19");
}

</style>
