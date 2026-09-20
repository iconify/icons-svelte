<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzpsuduik"/><path class="j835zw5-z"/><path class="kd8ucebka"/><path class="fd_yklwbw"/><path class="x-e8q2nft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:oven-outline-regular" {...props}></Icon>
<style>
:global(.fd_yklwbw) {
  d: path("M16 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.kd8ucebka) {
  d: path("M6 6h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.x-e8q2nft) {
  d: path("M7 12h10v6H7Z");
}

</style>
