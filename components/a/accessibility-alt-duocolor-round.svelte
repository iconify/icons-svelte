<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aamb_ippd"/><path class="l4cebudyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:accessibility-alt-duocolor-round" {...props}></Icon>
<style>
:global(.aamb_ippd) {
  stroke-opacity: 0.4;
  d: path("M11 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

:global(.l4cebudyd) {
  d: path("M5 10h14m-7 0v4l-4 6m4-6l4 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
