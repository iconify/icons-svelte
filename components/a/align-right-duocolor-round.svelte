<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3ynmu6py"/><path class="ydmp8rb4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-right-duocolor-round" {...props}></Icon>
<style>
:global(.h3ynmu6py) {
  stroke-opacity: 0.4;
  d: path("M20 3v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ydmp8rb4e) {
  d: path("M4 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H7a3 3 0 0 1-3-3m4 10a3 3 0 0 1 3-3h2a3 3 0 0 1 0 6h-2a3 3 0 0 1-3-3");
}

</style>
