<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-t_rcb_j"/><path class="dp8rry9sk"/><path class="ujtuebbmd"/><path class="k6fi9qmtq"/><path class="mqtixbwqo"/><path class="xsyfe-byx"/><path class="g_lky6blq"/><path class="qfgxpvbvs"/><path class="rb4zd2b4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:registry-duotone-thin" {...props}></Icon>
<style>
:global(.dp8rry9sk) {
  fill: currentColor;
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f-t_rcb_j) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g_lky6blq) {
  d: path("M10 13h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.qfgxpvbvs) {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rb4zd2b4c) {
  d: path("M10 17h5");
}

:global(.ujtuebbmd) {
  fill: currentColor;
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xsyfe-byx) {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
