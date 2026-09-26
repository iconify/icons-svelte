<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fkgek20zv"/><path class="pcfme6qxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-dashed-panel-sharp-two-tone" {...props}></Icon>
<style>
:global(.fkgek20zv) {
  stroke-opacity: 0.4;
  d: path("M9.5 3L14.5 3M21 9.5L21 14.5M3 8L3 3L7 3M17 3L21 3L21 7M16 21L21.0001 21L21 17");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pcfme6qxp) {
  d: path("M3 10.5L3 21L13.5 21M3.1464 20.8536L12.7929 11.2071");
}

</style>
