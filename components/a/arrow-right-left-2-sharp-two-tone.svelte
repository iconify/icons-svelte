<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eaenkfsiy"/><path class="niu2perjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-left-2-sharp-two-tone" {...props}></Icon>
<style>
:global(.eaenkfsiy) {
  stroke-opacity: 0.4;
  d: path("M1 7L2 7L12.2604 7L12.9144 7M7.8062 12.2939L8.1053 12L13.1934 7L8.1053 2L7.8062 1.7061");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.niu2perjr) {
  d: path("M23 17L22 17L11.7396 17L11.0856 17M16.1938 11.7061L15.8947 12L10.8066 17L15.8947 22L16.1938 22.2939");
}

</style>
