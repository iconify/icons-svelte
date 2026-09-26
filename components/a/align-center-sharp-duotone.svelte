<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c8ot_ib-j"/><path class="w_72eacvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-center-sharp-duotone" {...props}></Icon>
<style>
:global(.c8ot_ib-j) {
  stroke-opacity: 0.4;
  d: path("M2 3L22 3M2 15L22 15");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w_72eacvw) {
  d: path("M5 9L19 9M5 21L19 21");
}

</style>
