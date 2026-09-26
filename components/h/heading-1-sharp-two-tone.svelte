<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ouh-gobdj"/><path class="gfva2d1li"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-1-sharp-two-tone" {...props}></Icon>
<style>
:global(.gfva2d1li) {
  d: path("M16.4323 15.3965L19 13L19 20M15 20L23 20");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ouh-gobdj) {
  stroke-opacity: 0.4;
  d: path("M2 3L2 21M11 3L11 21M2 12L11 12");
}

</style>
