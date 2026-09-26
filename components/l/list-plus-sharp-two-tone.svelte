<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lke-2pb6e"/><path class="ue9ujtbdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-plus-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.lke-2pb6e) {
  stroke-opacity: 0.4;
  d: path("M1 4L23 4M1 11L23 11");
}

:global(.ue9ujtbdo) {
  d: path("M1 18L7 18M9 18L15 18M20 15L20 21M17 18L23 18");
}

</style>
