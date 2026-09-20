<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_w2e0bxp"/><path class="a0f0f2w0j"/><path class="qk-gt2bvd"/><path class="gwnaabclj"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lab-safety-duotone-thin" {...props}></Icon>
<style>
:global(.a0f0f2w0j) {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gwnaabclj) {
  d: path("M12 9v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_w2e0bxp) {
  fill: currentColor;
  d: path("m12 3 9 16H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qk-gt2bvd) {
  d: path("m12 3 9 16H3Z");
}

</style>
