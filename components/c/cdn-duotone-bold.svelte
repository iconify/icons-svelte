<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6e_qy8ax"/><path class="ic_6n1b1y"/><path class="o96cjofqo"/><path class="jea8fibeb"/><path class="kypa-ub6a"/><path class="zey5ebc0a"/><path class="b09_ctbde"/><path class="hzfx__bqu"/><path class="xq1pi7btv"/><path class="ng6jddb9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cdn-duotone-bold" {...props}></Icon>
<style>
:global(.b09_ctbde) {
  d: path("M2 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hzfx__bqu) {
  d: path("M18 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ic_6n1b1y) {
  fill: currentColor;
  d: path("M2 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jea8fibeb) {
  fill: currentColor;
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kypa-ub6a) {
  fill: currentColor;
  d: path("M18 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ng6jddb9r) {
  d: path("M18 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.o96cjofqo) {
  fill: currentColor;
  d: path("M18 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.x6e_qy8ax) {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xq1pi7btv) {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
