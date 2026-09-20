<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yyvm7xbin"/><path class="pldekmw0i"/><path class="lo7kp72nh"/><path class="nnidkxr0z"/><path class="pb1wrt76j"/><path class="k2lsbgbpx"/><path class="r7xk8o29f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:head-to-head-duotone-regular" {...props}></Icon>
<style>
:global(.k2lsbgbpx) {
  d: path("M14 17a4 4 0 0 1 8 0");
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nnidkxr0z) {
  d: path("M2 17a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pb1wrt76j) {
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pldekmw0i) {
  fill: currentColor;
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.yyvm7xbin) {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
