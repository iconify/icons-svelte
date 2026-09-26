<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uc2kjd4-r"/><path class="ta5v13f3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-horizontal-start-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ta5v13f3f) {
  d: path("M1 4L9 4");
}

:global(.uc2kjd4-r) {
  stroke-opacity: 0.4;
  d: path("M1 12L23 12M1 20L16 20");
}

</style>
