<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="clzz43bhf"/><path class="xqp_7g-qu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-inline-sharp-duotone" {...props}></Icon>
<style>
:global(.clzz43bhf) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 8L15 8C15.5523 8 16 8.4477 16 9L16 15C16 15.5523 15.5523 16 15 16L9 16C8.4477 16 8 15.5523 8 15L8 9C8 8.4477 8.4477 8 9 8Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xqp_7g-qu) {
  d: path("M2 3L22 3M2 21L22 21M2 12L6 12M18 12L22 12");
}

</style>
