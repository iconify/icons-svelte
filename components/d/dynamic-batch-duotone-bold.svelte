<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fx1ipbcbu"/><path class="gk2t7lsvx"/><path class="iave2ubph"/><path class="tc2f2bb6a"/><path class="vjm3bsazv"/><path class="ondrk6tkv"/><path class="k2mikoh9o"/><path class="k-nvl7u9w"/><path class="ai4lm938y"/><path class="eo360lbaq"/><path class="q485nsblw"/><path class="qd0z4jbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dynamic-batch-duotone-bold" {...props}></Icon>
<style>
:global(.ai4lm938y) {
  d: path("M3.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.eo360lbaq) {
  d: path("M8 4h2.5v16H8");
}

:global(.fx1ipbcbu) {
  fill: currentColor;
  d: path("M3.5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gk2t7lsvx) {
  fill: currentColor;
  d: path("M3.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iave2ubph) {
  fill: currentColor;
  d: path("M3.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k-nvl7u9w) {
  d: path("M3.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k2mikoh9o) {
  d: path("M3.5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ondrk6tkv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 9.5 19 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q485nsblw) {
  d: path("M13 12h4");
}

:global(.qd0z4jbov) {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tc2f2bb6a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4h2.5v16H8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vjm3bsazv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
