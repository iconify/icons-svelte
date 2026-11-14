<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxd-56bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flood-house-water" {...props}></Icon>
<style>
:global(.pxd-56bpm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12v-1.5L12 3.25l8.5 7.25V12m-18 3.75q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0m-19 4.5q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0");
}

</style>
