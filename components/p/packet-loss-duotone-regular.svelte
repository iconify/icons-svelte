<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dom865bkj"/><path class="ke6n18qno"/><path class="l5bkrjvtt"/><path class="zkem-xbdf"/><path class="t-euypbap"/><path class="iu1vklb-k"/><path class="cp6jnb7jw"/><path class="nqnw98byf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:packet-loss-duotone-regular" {...props}></Icon>
<style>
:global(.cp6jnb7jw) {
  d: path("M17 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dom865bkj) {
  fill: currentColor;
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iu1vklb-k) {
  d: path("M9 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ke6n18qno) {
  fill: currentColor;
  d: path("M9 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l5bkrjvtt) {
  fill: currentColor;
  d: path("M17 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t-euypbap) {
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zkem-xbdf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
