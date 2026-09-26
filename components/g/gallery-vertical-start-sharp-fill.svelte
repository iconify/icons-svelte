<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ipxpplbuj"/><path class="joa1ztv3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-start-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ipxpplbuj) {
  fill: currentColor;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 13C22 13.5523 21.5523 14 21 14L3 14C2.4477 14 2 13.5523 2 13L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

:global(.joa1ztv3m) {
  d: path("M4 17L20 17M6 21L18 21");
}

</style>
