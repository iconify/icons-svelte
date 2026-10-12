<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rxrolkl_q"/><path class="h0f7qujtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-down-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h0f7qujtt) {
  d: path("M7 22L7 3M2.7071 7.2929L7 3L11.2929 7.2929");
}

:global(.rxrolkl_q) {
  stroke-opacity: 0.4;
  d: path("M17 2L17 21M21.2929 16.7071L17 21L12.7071 16.7071");
}

</style>
