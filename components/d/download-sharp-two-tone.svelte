<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ccx_2u5al"/><path class="p3xqt9u1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:download-sharp-two-tone" {...props}></Icon>
<style>
:global(.ccx_2u5al) {
  stroke-opacity: 0.4;
  d: path("M12 2L12 14M7.7071 9.7071L12 14L16.2929 9.7071");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3xqt9u1y) {
  d: path("M4 17L4 21L20 21L20 17");
}

</style>
