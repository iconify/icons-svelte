<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yvotc3bin"/><path class="m1k1s7nte"/><path class="mi_m6achy"/><path class="l_9_psbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingress-traffic-outline-regular" {...props}></Icon>
<style>
:global(.l_9_psbce) {
  d: path("M21 6v12");
}

:global(.m1k1s7nte) {
  d: path("M10 12h10");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yvotc3bin) {
  d: path("M8 3H3v18h5");
}

</style>
