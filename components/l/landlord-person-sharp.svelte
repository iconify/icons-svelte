<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="vqgavtc7j"/><path class="trwu8yb8i"/><path class="y_atc20_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:landlord-person-sharp" {...props}></Icon>
<style>
:global(.trwu8yb8i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V15.5h11v5.75Zm14-.75V14l.53-.53l1.19-1.19l.53-.53l.53.53l1.19 1.19l.53.53v7.25h-4.5z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vqgavtc7j) {
  cx: 8.25px;
  cy: 7.25px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y_atc20_f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 17.25h.01");
}

</style>
