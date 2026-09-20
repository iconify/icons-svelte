<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i9a2h1bww"/><path class="y171prxam"/><path class="ctpjgucuu"/><path class="ynq2074_v"/><path class="tip34zbqw"/><path class="aam38ubkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:positional-encoding-duotone-bold" {...props}></Icon>
<style>
:global(.aam38ubkv) {
  d: path("M14 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ctpjgucuu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 16 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9a2h1bww) {
  fill: currentColor;
  d: path("M6 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.tip34zbqw) {
  d: path("M6 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y171prxam) {
  fill: currentColor;
  d: path("M14 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ynq2074_v) {
  d: path("m3 16 4 -4 4 4 4 -4 4 4");
}

</style>
