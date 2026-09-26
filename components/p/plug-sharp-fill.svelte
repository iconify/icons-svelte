<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m7bey1brc"/><path class="uvsqb_-sh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plug-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.m7bey1brc) {
  d: path("M9 1L9 8M15 1L15 8M12 17L12 23");
}

:global(.uvsqb_-sh) {
  fill: currentColor;
  d: path("M5 6L19 6C19.5523 6 20 6.4477 20 7L20 11C20 15.2802 16.2802 19 12 19C7.7198 19 4 15.2802 4 11L4 7C4 6.4477 4.4477 6 5 6Z");
  stroke: none;
}

</style>
