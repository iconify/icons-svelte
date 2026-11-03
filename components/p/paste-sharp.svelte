<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a5uo1zb2z"/><path clip-rule="evenodd" class="gp8a7l5bw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paste-sharp" {...props}></Icon>
<style>
:global(.a5uo1zb2z) {
  d: path("M5 4L2 4L2 21L9 21M13 4L16 4L16 8M5 2L13 2L13 7L5 7L5 2ZM18 11L12 11L12 22L22 22L22 15L18 11ZM18 11L18 15L22 15");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.gp8a7l5bw) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 11L22 15L18 15L18 11Z");
  stroke: none;
}

</style>
