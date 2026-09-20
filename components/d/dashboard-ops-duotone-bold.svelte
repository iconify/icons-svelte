<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f-t_rcb_j"/><path class="w72znacwv"/><path class="k6fi9qmtq"/><path class="mqtixbwqo"/><path class="fo1j3kuxp"/><path class="ao2a3wuly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dashboard-ops-duotone-bold" {...props}></Icon>
<style>
:global(.ao2a3wuly) {
  d: path("m5 17 4 -4 3 3 5 -5");
}

:global(.f-t_rcb_j) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fo1j3kuxp) {
  d: path("M17 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w72znacwv) {
  fill: currentColor;
  d: path("M17 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
