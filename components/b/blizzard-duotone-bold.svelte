<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c54duacdo"/><path class="gzvvr_cib"/><path class="gi7rbfrai"/><path class="guxnvybqm"/><path class="jyim9bnxo"/><path class="nrqy16b7j"/><path class="em798y7rn"/><path class="pvfbz5b4i"/><path class="wy-zn0bse"/><path class="e9z836b7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blizzard-duotone-bold" {...props}></Icon>
<style>
:global(.c54duacdo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e9z836b7m) {
  d: path("M18.5 15v6m-3 0 6 -6");
}

:global(.em798y7rn) {
  d: path("M6 12h14");
}

:global(.gi7rbfrai) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.guxnvybqm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 3v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzvvr_cib) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jyim9bnxo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 15v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.pvfbz5b4i) {
  d: path("M3 18h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wy-zn0bse) {
  d: path("M18.5 3v6m-3 0 6 -6");
}

</style>
