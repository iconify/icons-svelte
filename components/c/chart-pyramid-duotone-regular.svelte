<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x11b48bwb"/><path class="o9-mlwb2l"/><path class="lve95kzti"/><path class="kakiz1beo"/><path class="y4k_22w_l"/><path class="v9il_wb-q"/><path class="m-p3hbclp"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-pyramid-duotone-regular" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.kakiz1beo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lve95kzti) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.o9-mlwb2l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v9il_wb-q) {
  d: path("M6 10h12");
}

:global(.x11b48bwb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y4k_22w_l) {
  d: path("M8 5h8");
}

</style>
