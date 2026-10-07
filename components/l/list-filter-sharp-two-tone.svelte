<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0mba5b-a"/><path class="jslxdxt1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-filter-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jslxdxt1t) {
  d: path("M5 12L19 12M9 18L15 18");
}

:global(.v0mba5b-a) {
  stroke-opacity: 0.4;
  d: path("M1 6L23 6");
}

</style>
