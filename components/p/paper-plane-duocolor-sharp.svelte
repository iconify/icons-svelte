<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-31ttcxg"/><path class="xprgi_oxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paper-plane-duocolor-sharp" {...props}></Icon>
<style>
:global(.n-31ttcxg) {
  stroke-opacity: 0.4;
  d: path("m11 13l3-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xprgi_oxb) {
  d: path("M21 3L3 9l8 4l4 8z");
}

</style>
