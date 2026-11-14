<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_-cwb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lawn-length-tall" {...props}></Icon>
<style>
:global(.dz_-cwb4m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19M6 20.5Q6 12 3.5 4M10 20.5V3m4 17.5q0-9.5 3-17m1.5 17Q19 14 21.5 9");
}

</style>
