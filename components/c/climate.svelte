<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="im14o0bue"/><circle class="joko_go6x"/><path class="fze9urbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:climate" {...props}></Icon>
<style>
:global(.fze9urbic) {
  d: path("M17.25 2.75v.5m4 3.75h-.5m-3.5 4.25v-.5m-4-3.75h.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.im14o0bue) {
  d: path("M5.75 13.55V5.5a2.5 2.5 0 0 1 5 0v8.05a4.25 4.25 0 1 1-5 0M8.25 17V8.5");
}

:global(.joko_go6x) {
  cx: 17.25px;
  cy: 7px;
  r: 2px;
}

</style>
