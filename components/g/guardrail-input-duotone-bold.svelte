<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cxo2jiicg"/><path class="naa67qbfw"/><path class="fgef0hcge"/><path class="p5hd8ygud"/><path class="g15x_kbmg"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="p8yct170k"/><path class="ajw5g_mzy"/><path class="a-9s6wb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guardrail-input-duotone-bold" {...props}></Icon>
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

:global(.fgef0hcge) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g15x_kbmg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.5 9.5 13 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naa67qbfw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p5hd8ygud) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8yct170k) {
  d: path("M7 12h6");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>
