<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4k_22w_l"/><path class="v9il_wb-q"/><path class="m-p3hbclp"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-pyramid-outline-regular" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v9il_wb-q) {
  d: path("M6 10h12");
}

:global(.y4k_22w_l) {
  d: path("M8 5h8");
}

</style>
