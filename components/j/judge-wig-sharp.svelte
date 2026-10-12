<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tug9v5hrf"/><path class="n6qiawbxj"/><circle class="c-2k5unja"/><circle class="t9biy_bvw"/><circle class="ohs3i3bqs"/><circle class="jl82pcb2a"/><circle class="mup6iv_9j"/><circle class="e4492mmsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:judge-wig-sharp" {...props}></Icon>
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

:global(.n6qiawbxj) {
  d: path("m7.5 8.75l1.25 1l1-1l1-1l1.25 1l1.25 1l1-1l1-1l1.25 1");
}

:global(.ohs3i3bqs) {
  cx: 6.75px;
  cy: 18.75px;
  r: 1.75px;
}

:global(.t9biy_bvw) {
  cx: 6.75px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.tug9v5hrf) {
  d: path("M6.75 11.5V9a5.25 5.25 0 0 1 10.5 0v2.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
