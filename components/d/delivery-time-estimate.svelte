<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yskhiqbib"/><path class="lb18hac-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delivery-time-estimate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb18hac-a) {
  d: path("M14 8.5V12l2.5 1.5M2 8.5h1.75M2 12h1.75M2 15.5h1.75");
}

:global(.yskhiqbib) {
  d: path("M6.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>
