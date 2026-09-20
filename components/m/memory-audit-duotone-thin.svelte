<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8c8atiya"/><path class="g7y1om9dd"/><path class="bjzalvuax"/><path class="n0n63pb2v"/><path class="jotdonbiv"/><path class="a-p6m2b3f"/><path class="ux6apgnet"/><path class="aes764-qd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-audit-duotone-thin" {...props}></Icon>
<style>
:global(.a-p6m2b3f) {
  d: path("M10.5 6H16");
}

:global(.aes764-qd) {
  d: path("M10.5 10H16");
}

:global(.bjzalvuax) {
  fill: currentColor;
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g7y1om9dd) {
  fill: currentColor;
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jotdonbiv) {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m8c8atiya) {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.ux6apgnet) {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
