<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nco8t8gvh"/><path class="h04w61b7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bimetallic-strip" {...props}></Icon>
<style>
:global(.h04w61b7w) {
  d: path("M3 13.75q9-7 18 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nco8t8gvh) {
  d: path("M3 17.5q9-7 18 0M3 10q9-7 18 0");
}

</style>
