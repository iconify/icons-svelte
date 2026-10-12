<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kmq9dq93n"/><path class="vpebmwb2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-right-3-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kmq9dq93n) {
  stroke-opacity: 0.4;
  d: path("M14 7L13 7L2.7396 7L2.0856 7M7.1888 12.3005L6.8947 12L2 7L6.8947 2L7.1888 1.6995");
}

:global(.vpebmwb2f) {
  d: path("M10 17L11 17L21.2604 17L21.9144 17M16.8112 11.6995L17.1053 12L22 17L17.1053 22L16.8112 22.3005");
}

</style>
