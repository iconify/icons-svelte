<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2663rn1y"/><path class="kywqclbap"/><path class="dx3zvablc"/><path class="xjv_jxbvs"/><path class="fnf6pdbdu"/><path class="prhskmb-v"/><path class="ofbkge5tm"/><path class="j7bay-umk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chandelier-duotone-regular" {...props}></Icon>
<style>
:global(.dx3zvablc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fnf6pdbdu) {
  d: path("M12 3v6");
}

:global(.j7bay-umk) {
  d: path("M18 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kywqclbap) {
  fill: currentColor;
  d: path("M18 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n2663rn1y) {
  fill: currentColor;
  d: path("M2 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ofbkge5tm) {
  d: path("M2 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.prhskmb-v) {
  d: path("M4 16c0 -5 4 -7 8 -7s8 2 8 7");
}

:global(.xjv_jxbvs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16c0 -5 4 -7 8 -7s8 2 8 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
