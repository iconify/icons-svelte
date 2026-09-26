<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ouh-gobdj"/><path class="zw0h7bb4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-4-sharp-two-tone" {...props}></Icon>
<style>
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

:global(.zw0h7bb4f) {
  d: path("M17 12L17 17.5L23 17.5M21 12L21 21");
}

</style>
