<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cbdwf_bsy"/><path class="lu0dhdb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:download-pending" {...props}></Icon>
<style>
:global(.cbdwf_bsy) {
  d: path("M4 15v3a2 2 0 0 0 2 2h6.25M12 3.5V15m-4.5-4.5L12 15l4.5-4.5M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lu0dhdb5q) {
  d: path("M18 16.5V18l1 1");
}

</style>
