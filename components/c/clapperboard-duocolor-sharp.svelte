<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwwv6-b1v"/><path class="gke1ejk8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clapperboard-duocolor-sharp" {...props}></Icon>
<style>
:global(.gke1ejk8o) {
  d: path("M3 9h18v12H3Zm0-3l16-3l.563 3l-16 3zm5.333-1l.563 3m4.77-4l.563 3");
}

:global(.hwwv6-b1v) {
  stroke-opacity: 0.4;
  d: path("m10 12l5 3l-5 3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
