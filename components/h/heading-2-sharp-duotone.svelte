<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ouh-gobdj"/><path class="l219k3blr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-2-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l219k3blr) {
  d: path("M17 16L17 15C17 13.8954 17.8954 13 19 13C20.1046 13 21 13.8954 21 15C21 15.6037 20.7273 16.1751 20.258 16.5548L17 20L23 20");
}

:global(.ouh-gobdj) {
  stroke-opacity: 0.4;
  d: path("M2 3L2 21M11 3L11 21M2 12L11 12");
}

</style>
