<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux_uic52u"/><path class="ceqr-6wjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:award-category" {...props}></Icon>
<style>
:global(.ceqr-6wjb) {
  d: path("m5 10.75l-1 5l3-1.5l3 1.5l-1-5m5-3h6.5m-6.5 6h6.5m-17 6h17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux_uic52u) {
  d: path("M3.5 7.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
