<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="e6gq_mbtj"/><path class="qe97cg-lx"/><path class="yt1wgcb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:activation-duotone-regular" {...props}></Icon>
<style>
:global(.e6gq_mbtj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 17h7l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gb7yzvvzz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.yt1wgcb2d) {
  d: path("M5 17h7l7 -7");
}

</style>
