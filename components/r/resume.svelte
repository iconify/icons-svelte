<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="i9tm6qb-c"/><circle class="n-dokxb-c"/><path class="opr54_b6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:resume" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9tm6qb-c) {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5");
}

:global(.jz9wy2bsc) {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

:global(.n-dokxb-c) {
  cx: 9.25px;
  cy: 10.5px;
  r: 1.75px;
}

:global(.opr54_b6k) {
  d: path("M13 11.75h2.25m-7 3.5h7.5M8.25 18h7.5");
}

</style>
