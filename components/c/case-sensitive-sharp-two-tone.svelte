<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h608s2btr"/><path class="tw044-bwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:case-sensitive-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h608s2btr) {
  stroke-opacity: 0.4;
  d: path("M1.93 18.627L7.002 6L12.074 18.627M4.19 13H9.813");
}

:global(.tw044-bwh) {
  d: path("M22.002 10V19M22.002 15C22.002 16.657 20.659 18 19.002 18C17.345 18 16.002 16.657 16.002 15C16.002 13.343 17.345 12 19.002 12C20.659 12 22.002 13.343 22.002 15Z");
}

</style>
