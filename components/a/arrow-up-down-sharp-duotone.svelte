<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pqdsnpb8o"/><path class="pwnnr1bts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-down-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqdsnpb8o) {
  stroke-opacity: 0.4;
  d: path("M18 2L18 21M21.2929 17.7071L18 21L14.7071 17.7071");
}

:global(.pwnnr1bts) {
  d: path("M6 22L6 3M9.2929 6.2929L6 3L2.7071 6.2929");
}

</style>
