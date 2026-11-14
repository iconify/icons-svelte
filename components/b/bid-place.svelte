<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d3_x25z6d"/><path class="p2y3u65sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bid-place" {...props}></Icon>
<style>
:global(.d3_x25z6d) {
  d: path("M3.75 8.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p2y3u65sq) {
  d: path("M8 7.25L9.75 6v4.5M9.5 14v7.5M18 15v6m-3-3h6");
}

</style>
