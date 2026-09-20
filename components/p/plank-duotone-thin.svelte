<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wznabhb2m"/><path class="kbnxaxalc"/><path class="jkimc-oto"/><path class="stjf13gff"/><path class="rpp4spbxo"/><path class="bhkm33b7x"/><path class="x8_u9-97v"/><path class="zpp3fehhr"/><path class="zuuhu6bzg"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plank-duotone-thin" {...props}></Icon>
<style>
:global(.bhkm33b7x) {
  d: path("M2 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkimc-oto) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kbnxaxalc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 8 4 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rpp4spbxo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.stjf13gff) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wznabhb2m) {
  fill: currentColor;
  d: path("M2 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8_u9-97v) {
  d: path("m6 8 4 4h10");
}

:global(.zpp3fehhr) {
  d: path("M10 12v3");
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>
