<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mc1e3dblj"/><path class="r23rcibvv"/><path class="fq7shjbor"/><path class="mzp9zz-op"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:origami-duotone-bold" {...props}></Icon>
<style>
:global(.fq7shjbor) {
  d: path("M3 14h18c-1 3 -4 6 -9 6s-8 -3 -9 -6");
}

:global(.mc1e3dblj) {
  fill: currentColor;
  d: path("M3 14h18c-1 3 -4 6 -9 6s-8 -3 -9 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mzp9zz-op) {
  d: path("M11 11V3l8 8Z");
}

:global(.r23rcibvv) {
  fill: currentColor;
  d: path("M11 11V3l8 8Z");
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
