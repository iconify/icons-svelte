<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kp5q9696o"/><path class="ua6hpxbwj"/><path class="gmcwnnbyg"/><path class="p4a4wbc0p"/><path class="yvotc3bin"/><path class="m1k1s7nte"/><path class="mi_m6achy"/><path class="l_9_psbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingress-traffic-duotone-regular" {...props}></Icon>
<style>
:global(.gmcwnnbyg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kp5q9696o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3H3v18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

:global(.p4a4wbc0p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ua6hpxbwj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yvotc3bin) {
  d: path("M8 3H3v18h5");
}

</style>
