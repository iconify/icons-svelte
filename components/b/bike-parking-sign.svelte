<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7piovbwx"/><path class="d327vabxr"/><path class="rwy2l9_ze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bike-parking-sign" {...props}></Icon>
<style>
:global(.d327vabxr) {
  d: path("M5.25 12.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8.5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rwy2l9_ze) {
  d: path("M7.75 12.25L10.5 8h4l1.75 4.25");
}

:global(.z7piovbwx) {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14V6A3.5 3.5 0 0 1 6 2.5m6 15v4");
}

</style>
