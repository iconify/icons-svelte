<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="i9tm6qb-c"/><circle class="qhm14obvb"/><path class="lak5g3bpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-key" {...props}></Icon>
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

:global(.lak5g3bpz) {
  d: path("M11.25 14.75h4.25m-1 0v1.75");
}

:global(.qhm14obvb) {
  cx: 9.5px;
  cy: 14.75px;
  r: 1.75px;
}

</style>
