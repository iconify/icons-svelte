<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zamthyb_j"/><path class="j21bw5e7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-bottom-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.j21bw5e7j) {
  d: path("M15 4L23 4");
}

:global(.zamthyb_j) {
  stroke-opacity: 0.4;
  d: path("M3 12L23 12M1 20L15 20");
}

</style>
