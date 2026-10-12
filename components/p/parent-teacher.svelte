<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z0_wr4gzy"/><circle class="c-2k5unja"/><path class="fwpet3b4e"/><circle class="jl82pcb2a"/><path class="zoaae6bwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parent-teacher" {...props}></Icon>
<style>
:global(.c-2k5unja) {
  cx: 6.75px;
  cy: 12.25px;
  r: 1.75px;
}

:global(.fwpet3b4e) {
  d: path("M3 21.25v-1a3.75 3.75 0 0 1 7.5 0v1Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jl82pcb2a) {
  cx: 17.25px;
  cy: 12.25px;
  r: 1.75px;
}

:global(.z0_wr4gzy) {
  d: path("M7.5 2.75h9a2 2 0 0 1 2 2V6a2 2 0 0 1-2 2h-3.25L12 9.5L10.75 8H7.5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2M9 5.4h6");
}

:global(.zoaae6bwy) {
  d: path("M13.5 21.25v-1a3.75 3.75 0 0 1 7.5 0v1Z");
}

</style>
