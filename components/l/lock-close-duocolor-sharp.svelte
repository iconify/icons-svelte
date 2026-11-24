<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cr709fn9c"/><path class="kskc15b9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-close-duocolor-sharp" {...props}></Icon>
<style>
:global(.cr709fn9c) {
  stroke-opacity: 0.4;
  d: path("m10 13l4 4m0-4l-4 4");
}

:global(.kskc15b9j) {
  d: path("M4 9h16v12H4Zm4 0V7a4 4 0 1 1 8 0v2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
