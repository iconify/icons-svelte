<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t00g54bkw"/><path class="l7dpryp5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-pin-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.l7dpryp5e) {
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t00g54bkw) {
  stroke-opacity: 0.4;
  d: path("M15 13h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

</style>
