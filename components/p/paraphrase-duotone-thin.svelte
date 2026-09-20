<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="hf_gtezns"/><path class="osltrsbvo"/><path class="hovg28bac"/><path class="m89us6n4x"/><path class="ltgrz9-xn"/><path class="xgrfb-bqu"/><path class="xyj-l9cjp"/><path class="f26bn-hui"/><path class="l8vl6rdup"/><path class="dti01qb8s"/><path class="l76jezbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paraphrase-duotone-thin" {...props}></Icon>
<style>
:global(.dti01qb8s) {
  d: path("M16 9v6");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f26bn-hui) {
  d: path("M8 9v6");
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hovg28bac) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 12.5 8 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l76jezbpv) {
  d: path("M13.5 11.5 16 9l2.5 2.5");
}

:global(.l8vl6rdup) {
  d: path("M5.5 12.5 8 15l2.5 -2.5");
}

:global(.ltgrz9-xn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 11.5 16 9l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m89us6n4x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.osltrsbvo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
