<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y3fcv3bfg"/><path class="pzkmj5byd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-align-left-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzkmj5byd) {
  d: path("M2 3L22 3M2 21L22 21");
}

:global(.y3fcv3bfg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6L13 6C13.5523 6 14 6.4477 14 7L14 17C14 17.5523 13.5523 18 13 18L3 18C2.4477 18 2 17.5523 2 17L2 7C2 6.4477 2.4477 6 3 6Z");
  stroke: none;
}

</style>
