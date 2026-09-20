<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cxo2jiicg"/><path class="its1e1bwq"/><path class="dbfzjzb3n"/><path class="zls5rf_kj"/><path class="jaml3ccon"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="p8yct170k"/><path class="ajw5g_mzy"/><path class="a-9s6wb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guardrail-input-duotone-regular" {...props}></Icon>
<style>
:global(.a-9s6wb0y) {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ajw5g_mzy) {
  d: path("M10.5 9.5 13 12l-2.5 2.5");
}

:global(.cxo2jiicg) {
  fill: currentColor;
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dbfzjzb3n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.its1e1bwq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jaml3ccon) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 9.5 13 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8yct170k) {
  d: path("M7 12h6");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

:global(.zls5rf_kj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
