<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr897rhbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:absence-tracking" {...props}></Icon>
<style>
:global(.lr897rhbh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3v9q0 3 3 3h6.25M7 15v4.5m-4 0h8m3.5-8v8m2.5-8v8m2.5-8v8m2.5-8v8m-8.75-1.75L22 13");
}

</style>
