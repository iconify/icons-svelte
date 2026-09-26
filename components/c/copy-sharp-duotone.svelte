<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c-fn48bus"/><path class="gpiqd5sil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:copy-sharp-duotone" {...props}></Icon>
<style>
:global(.c-fn48bus) {
  stroke-opacity: 0.4;
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.gpiqd5sil) {
  fill: currentColor;
  d: path("M8 7L22 7C22.5523 7 23 7.4477 23 8L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7Z");
  stroke: none;
}

</style>
