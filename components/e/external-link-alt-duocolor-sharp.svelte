<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tr6fl5zng"/><path class="yuu8r1_fu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:external-link-alt-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tr6fl5zng) {
  stroke-opacity: 0.4;
  d: path("M4 15h5v5m0-5l-6 6");
}

:global(.yuu8r1_fu) {
  d: path("M14 19h5V5H5v5");
}

</style>
