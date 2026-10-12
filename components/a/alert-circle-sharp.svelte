<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="c_1nltq2j"/><path class="u_3_acqhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alert-circle-sharp" {...props}></Icon>
<style>
:global(.c_1nltq2j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.25v5.25");
}

:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u_3_acqhp) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
