<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhnxmhb1c"/><path class="vbpe02bto"/><path class="x355oor5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:radiotherapy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhnxmhb1c) {
  d: path("m12 9.5l1.5 2.25l2.75.75V15l1.5 2.5l-3.25.75l-1.5 2.5l-2.5-1.5l-3.25-.5l.75-3L7.25 13l2.25-1Z");
}

:global(.vbpe02bto) {
  fill: currentColor;
  d: path("M10.75 14c1-.75 2.75-.5 3 .75c.25 1.5-.5 2.5-2 2.25c-1.25 0-1.75-2.25-1-3");
}

:global(.x355oor5l) {
  d: path("m3 3l5 6.5m4-7v4.75M21 3l-5 6.5");
}

</style>
