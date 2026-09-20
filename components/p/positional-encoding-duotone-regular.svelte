<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i9a2h1bww"/><path class="y171prxam"/><path class="gslnvcq4w"/><path class="ynq2074_v"/><path class="tip34zbqw"/><path class="aam38ubkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:positional-encoding-duotone-regular" {...props}></Icon>
<style>
:global(.aam38ubkv) {
  d: path("M14 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gslnvcq4w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 16 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9a2h1bww) {
  fill: currentColor;
  d: path("M6 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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
