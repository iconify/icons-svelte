<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="trtifv9xg"/><path class="k2m0qnbly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:case-upper-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k2m0qnbly) {
  d: path("M15.941 18.67L18.998 10L22.055 18.67M16.882 16H21.114");
}

:global(.trtifv9xg) {
  stroke-opacity: 0.4;
  d: path("M1.93 18.63L7.002 6L12.074 18.63M4.19 13H9.813");
}

</style>
