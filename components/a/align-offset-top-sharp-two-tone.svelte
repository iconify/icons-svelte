<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eym-d9b2y"/><path class="n7sq4abaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-top-sharp-two-tone" {...props}></Icon>
<style>
:global(.eym-d9b2y) {
  stroke-opacity: 0.4;
  d: path("M1 4L15 4M3 12L23 12");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.n7sq4abaq) {
  d: path("M15 20L23 20");
}

</style>
