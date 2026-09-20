<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lmrvcn97u"/><path class="mn_ax0bot"/><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="gkpqkuwgc"/><path class="fqm6mobxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:key-alert-duotone-bold" {...props}></Icon>
<style>
:global(.a0z9iab1m) {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

:global(.drjiz3bcf) {
  d: path("M12 21h2.5");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.fqm6mobxy) {
  d: path("M11 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gkpqkuwgc) {
  d: path("M12 5.5v3");
}

:global(.lmrvcn97u) {
  fill: currentColor;
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mn_ax0bot) {
  fill: currentColor;
  d: path("M11 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xidycypec) {
  d: path("M12 18h3");
}

</style>
