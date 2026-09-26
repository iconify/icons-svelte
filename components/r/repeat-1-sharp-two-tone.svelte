<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kvt67ihpg"/><path class="yv4c-x_5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:repeat-1-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kvt67ihpg) {
  stroke-opacity: 0.4;
  d: path("M3 18L21 18L21 5L15.5 5M6.2929 14.7071L3 18L6.2929 21.2929");
}

:global(.yv4c-x_5c) {
  d: path("M10.5547 4.2968L12.5 3L12.5 10M3 12L3 5L8 5");
}

</style>
