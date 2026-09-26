<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fkgek20zv"/><path class="mcs_s1bmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-dashed-panel-sharp-duotone" {...props}></Icon>
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

:global(.mcs_s1bmd) {
  d: path("M3.4751 15.5L15 15.5M9.3094 9.7045L3.2399 15.5L9.2898 21.2768");
}

</style>
