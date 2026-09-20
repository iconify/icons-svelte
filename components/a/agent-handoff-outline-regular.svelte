<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zq_pavbka"/><path class="pkx_lss1s"/><path class="tr3i0d91k"/><path class="lhz2jzbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-handoff-outline-regular" {...props}></Icon>
<style>
:global(.lhz2jzbtp) {
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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
