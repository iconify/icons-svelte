<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="iatyddcmd"/><circle class="f3klz9dak"/><circle class="rctbt0bba"/><path class="l-a3p-biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:per-mille" {...props}></Icon>
<style>
:global(.f3klz9dak) {
  cx: 12.25px;
  cy: 17.5px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iatyddcmd) {
  cx: 5.75px;
  cy: 6.75px;
  r: 2.25px;
}

:global(.l-a3p-biv) {
  d: path("m16.75 3.75l-13 16.5");
}

:global(.rctbt0bba) {
  cx: 18.75px;
  cy: 17.5px;
  r: 2.25px;
}

</style>
