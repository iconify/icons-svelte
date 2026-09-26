<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dk4_o5c1g"/><path class="tsngy8x8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-down-sharp-duotone" {...props}></Icon>
<style>
:global(.dk4_o5c1g) {
  stroke-opacity: 0.4;
  d: path("M4 1L4 16M12 1L12 23");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tsngy8x8e) {
  d: path("M20 1L20 9");
}

</style>
