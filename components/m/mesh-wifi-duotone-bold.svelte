<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r761c-bxw"/><path class="crm2eebhm"/><path class="woeos_2de"/><path class="tkhdrzhel"/><path class="pxr7oenpw"/><path class="h3vqphsll"/><path class="wc595gblk"/><path class="bo88vlbuz"/><path class="e030h51ix"/><path class="elc06ob4j"/><path class="i2p3oabgb"/><path class="fiatxpbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mesh-wifi-duotone-bold" {...props}></Icon>
<style>
:global(.bo88vlbuz) {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.crm2eebhm) {
  fill: currentColor;
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e030h51ix) {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.elc06ob4j) {
  d: path("M8 8h8");
}

:global(.fiatxpbey) {
  d: path("m17 10 -4 4");
}

:global(.h3vqphsll) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 10 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i2p3oabgb) {
  d: path("m7 10 4 4");
}

:global(.pxr7oenpw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r761c-bxw) {
  fill: currentColor;
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.tkhdrzhel) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.woeos_2de) {
  fill: currentColor;
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
