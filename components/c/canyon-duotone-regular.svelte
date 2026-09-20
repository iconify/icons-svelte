<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dfymwbb_b"/><path class="c7fh5sbkl"/><path class="y99o76bdn"/><path class="lbkuffism"/><path class="tqteed1fm"/><path class="hqkel0bnd"/><path class="uaurn5bqf"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:canyon-duotone-regular" {...props}></Icon>
<style>
:global(.c7fh5sbkl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22 3h-6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dfymwbb_b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 3h6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hqkel0bnd) {
  d: path("M22 3h-6v18");
}

:global(.lbkuffism) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.tqteed1fm) {
  d: path("M2 3h6v18");
}

:global(.uaurn5bqf) {
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
}

:global(.y99o76bdn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
