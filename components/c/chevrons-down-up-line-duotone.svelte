<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfrug7s3s"/><path class="uyjuokbvi"/><path class="vtwk979ug"/><path class="xggl6t9lq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-down-up-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfrug7s3s) {
  d: path("M18 21L12 15L6 21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.uyjuokbvi) {
  d: path("M9 18L12 15L18 21");
}

:global(.vtwk979ug) {
  d: path("M18 3L12 9L6 3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.xggl6t9lq) {
  d: path("M9 6L12 9L18 3");
}

</style>
