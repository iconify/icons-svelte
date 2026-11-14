<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el079s0gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:park-box" {...props}></Icon>
<style>
:global(.el079s0gy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.733 11.304l2.25-3.5A1.75 1.75 0 0 1 8.455 7H19.25A1.75 1.75 0 0 1 21 8.75v3.5A1.75 1.75 0 0 1 19.25 14H6.205a1.75 1.75 0 0 1-1.472-2.696M3 17h18");
}

</style>
