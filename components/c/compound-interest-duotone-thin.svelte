<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhy5nnbig"/><path class="f8es0kdly"/><path class="lvy4ugbrg"/><path class="o_ssmh9ez"/><path class="bok4-ne0z"/><path class="ik3tfcbzx"/><path class="sim8sii7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compound-interest-duotone-thin" {...props}></Icon>
<style>
:global(.bok4-ne0z) {
  d: path("m8 16 8 -8");
}

:global(.f8es0kdly) {
  fill: currentColor;
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ik3tfcbzx) {
  d: path("M7 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lvy4ugbrg) {
  fill: currentColor;
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.sim8sii7h) {
  d: path("M13 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zhy5nnbig) {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
