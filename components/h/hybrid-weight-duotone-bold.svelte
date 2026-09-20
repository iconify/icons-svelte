<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m3tfe9bwc"/><path class="mvzssg28o"/><path class="gl-be55-z"/><path class="mjze8rg7o"/><path class="k-qzacblk"/><path class="m5kk8acjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hybrid-weight-duotone-bold" {...props}></Icon>
<style>
:global(.gl-be55-z) {
  fill: currentColor;
  d: path("M14 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k-qzacblk) {
  d: path("M7.5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.m3tfe9bwc) {
  fill: currentColor;
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m5kk8acjv) {
  d: path("M14 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mjze8rg7o) {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

:global(.mvzssg28o) {
  fill: currentColor;
  d: path("M7.5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

</style>
