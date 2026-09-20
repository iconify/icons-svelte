<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow9nvovdw"/><path class="thz-qac8s"/><path class="lf6jf1bxr"/><path class="yiqwex2_u"/><path class="ksgk5nb8u"/><path class="vtcxv5brk"/><path class="b7nacdcee"/><path class="d223d_x9q"/><path class="d_scobift"/><path class="ymrjh3b_x"/><path class="k2jd848hu"/><path class="f2m4wubik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:answer-synthesis-duotone-regular" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.d_scobift) {
  d: path("M3 18h6");
}

:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.f2m4wubik) {
  d: path("M13 12h8");
}

:global(.k2jd848hu) {
  d: path("m9 16 4 -4");
}

:global(.ksgk5nb8u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lf6jf1bxr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ow9nvovdw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.thz-qac8s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vtcxv5brk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yiqwex2_u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymrjh3b_x) {
  d: path("m9 8 4 4");
}

</style>
