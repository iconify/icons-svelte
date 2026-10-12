<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="acsttngms"/><path class="r8i1ocbvm"/><circle class="ms78u9z4z"/><circle class="np3bxhlxr"/><path class="ojslz54ld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:earbud-case-sharp" {...props}></Icon>
<style>
:global(.acsttngms) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.75h17.5v3a5.5 5.5 0 0 1-5.5 5.5h-6.5a5.5 5.5 0 0 1-5.5-5.5Zm0 2.5h17.5");
}

:global(.ms78u9z4z) {
  cx: 8.25px;
  cy: 5.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.np3bxhlxr) {
  cx: 15.75px;
  cy: 5.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ojslz54ld) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6.75v4m6.5-4v4");
}

:global(.r8i1ocbvm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
