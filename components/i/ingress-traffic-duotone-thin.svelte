<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_xrh301h"/><path class="s74cfob_f"/><path class="gv3gpab3b"/><path class="eu5thqbry"/><path class="yvotc3bin"/><path class="m1k1s7nte"/><path class="mi_m6achy"/><path class="l_9_psbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingress-traffic-duotone-thin" {...props}></Icon>
<style>
:global(.eu5thqbry) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gv3gpab3b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l_9_psbce) {
  d: path("M21 6v12");
}

:global(.l_xrh301h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3H3v18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m1k1s7nte) {
  d: path("M10 12h10");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.s74cfob_f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yvotc3bin) {
  d: path("M8 3H3v18h5");
}

</style>
