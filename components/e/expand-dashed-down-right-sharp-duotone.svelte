<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="am1_grbcw"/><path class="kcu1pgbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-right-sharp-duotone" {...props}></Icon>
<style>
:global(.am1_grbcw) {
  d: path("M6 10L6 21M2.7071 17.7071L6 21L9.2929 17.7071M10 6L21 6M17.7071 9.2929L21 6L17.7071 2.7071");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kcu1pgbck) {
  stroke-opacity: 0.4;
  d: path("M21 12L21 15.3333M21 17.3333L21 21L17.3333 21M15.3333 21L12 21");
}

</style>
