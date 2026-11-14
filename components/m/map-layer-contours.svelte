<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cdwlxwb8h"/><path class="xwc9nmkut"/><path class="redv2sb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-layer-contours" {...props}></Icon>
<style>
:global(.cdwlxwb8h) {
  d: path("M3 13C3 7.5 6.5 3 12.5 3C18 3 21 5.5 21 10c0 4-.5 11-6.5 11C8 21 3 18.5 3 13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.redv2sb0u) {
  d: path("M11.75 10.75c0-1.25 1-1.75 2-1.75s1.5.75 1.5 1.5c0 1-.75 1.5-1.75 1.5s-1.75-.25-1.75-1.25");
}

:global(.xwc9nmkut) {
  d: path("M8.25 11c0-3.25 2.75-5 5.25-5c3 0 4.75 1.5 4.75 4c0 3-1.25 5.5-4.5 5.5S8.25 14 8.25 11");
}

</style>
