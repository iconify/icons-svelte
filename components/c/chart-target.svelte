<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cyk7jm02b"/><path class="dmn0ui_hy"/><path class="oxxnebbjv"/><path class="fsbyttsma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-target" {...props}></Icon>
<style>
:global(.cyk7jm02b) {
  d: path("M6.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.dmn0ui_hy) {
  d: path("M10.5 10a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.fsbyttsma) {
  d: path("m2.5 21.5l3-5.5L8 19l6-9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oxxnebbjv) {
  fill: currentColor;
  d: path("M14 10h.01");
}

</style>
