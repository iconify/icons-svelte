<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="fwak83qxa"/><path class="fv5pcnpmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:curling-button" {...props}></Icon>
<style>
:global(.fv5pcnpmp) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.fwak83qxa) {
  d: path("M6.25 12a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
