<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dy0hckkum"/><path class="nnp_nlbyr"/><path class="k8_tyfz0x"/><path class="utjpr2bvm"/><path class="hubgvrbhc"/><path class="g9_x3sqrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:oauth-duotone-thin" {...props}></Icon>
<style>
:global(.dy0hckkum) {
  fill: currentColor;
  d: path("M8 11a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g9_x3sqrx) {
  d: path("M6 14h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hubgvrbhc) {
  d: path("M2 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.k8_tyfz0x) {
  d: path("M8 11a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
}

:global(.nnp_nlbyr) {
  fill: currentColor;
  d: path("M2 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.utjpr2bvm) {
  d: path("M11 9a4 4 0 0 1 8 0");
}

</style>
