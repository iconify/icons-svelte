<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jl1u9iyxw"/><path class="e9i-mpbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:autoplay-duocolor-sharp" {...props}></Icon>
<style>
:global(.e9i-mpbsf) {
  d: path("M20 16a8.944 8.944 0 1 1 0-8m-4 0h4V4");
}

:global(.jl1u9iyxw) {
  stroke-opacity: 0.4;
  d: path("m10 8l6 4l-6 4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
