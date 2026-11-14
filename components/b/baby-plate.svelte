<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="won6j-zpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-plate" {...props}></Icon>
<style>
:global(.won6j-zpn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m0 0h15m-7.5 0v7.5M19 7a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0m1.5 2.5V20");
}

</style>
