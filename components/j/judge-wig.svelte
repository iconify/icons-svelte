<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tug9v5hrf"/><path class="se0yzabbi"/><circle class="c-2k5unja"/><circle class="t9biy_bvw"/><circle class="ohs3i3bqs"/><circle class="jl82pcb2a"/><circle class="mup6iv_9j"/><circle class="e4492mmsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:judge-wig" {...props}></Icon>
<style>
:global(.c-2k5unja) {
  cx: 6.75px;
  cy: 12.25px;
  r: 1.75px;
}

:global(.e4492mmsp) {
  cx: 17.25px;
  cy: 18.75px;
  r: 1.75px;
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

:global(.mup6iv_9j) {
  cx: 17.25px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.ohs3i3bqs) {
  cx: 6.75px;
  cy: 18.75px;
  r: 1.75px;
}

:global(.se0yzabbi) {
  d: path("M7.5 8.75q1.25 1 2.25 0t2.25 0t2.25 0t2.25 0");
}

:global(.t9biy_bvw) {
  cx: 6.75px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.tug9v5hrf) {
  d: path("M6.75 11.5V9a5.25 5.25 0 0 1 10.5 0v2.5Z");
}

</style>
