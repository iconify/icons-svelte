<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r4q1s-bug"/><path class="z3d6c58bu"/><path class="nz2n46bes"/><path class="t46_l1b3y"/><path class="o8adkomvn"/><path class="qrnoe1--b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-from-line-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nz2n46bes) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o8adkomvn) {
  d: path("M12 8v12");
}

:global(.qrnoe1--b) {
  d: path("m8 16 4 4 4 -4");
}

:global(.r4q1s-bug) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t46_l1b3y) {
  d: path("M7 4h10");
}

:global(.z3d6c58bu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
