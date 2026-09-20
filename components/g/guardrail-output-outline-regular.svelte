<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="iedujiqkb"/><path class="ognhgbb3v"/><path class="pz3wsjbwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guardrail-output-outline-regular" {...props}></Icon>
<style>
:global(.iedujiqkb) {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ognhgbb3v) {
  d: path("M10.5 12H17");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.pz3wsjbwy) {
  d: path("M14.5 9.5 17 12l-2.5 2.5");
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>
