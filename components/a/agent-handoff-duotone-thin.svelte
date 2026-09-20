<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrfcflbzs"/><path class="fjehl4tkv"/><path class="ivmzqpb5e"/><path class="cvr9mcbfs"/><path class="zq_pavbka"/><path class="pkx_lss1s"/><path class="tr3i0d91k"/><path class="lhz2jzbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-handoff-duotone-thin" {...props}></Icon>
<style>
:global(.cvr9mcbfs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fjehl4tkv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 14 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivmzqpb5e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 10H14v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lhz2jzbtp) {
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.nrfcflbzs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pkx_lss1s) {
  d: path("m10 14 2.5 -2.5");
}

:global(.tr3i0d91k) {
  d: path("M11.5 10H14v2.5");
}

:global(.zq_pavbka) {
  d: path("M7.27 15.28a3 3 0 1 1 -2.54 0");
}

</style>
