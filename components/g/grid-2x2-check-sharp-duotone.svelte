<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p0df1zbcw"/><path class="ypxhweb_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-check-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0df1zbcw) {
  stroke-opacity: 0.4;
  d: path("M2 11L20 11L20 2L2 2L2 20L11 20L11 2");
}

:global(.ypxhweb_v) {
  d: path("M15.7055 19.2971L18.3333 22L22.1467 15.76");
}

</style>
