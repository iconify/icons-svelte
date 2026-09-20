<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ycftzzhuq"/><path class="hnba5kd6n"/><path class="z_cql0b5h"/><path class="km2_vvbqp"/><path class="l8dn9jbyp"/><path class="sg1q03b0n"/><path class="zgowxqjxj"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:in-flight-meal-duotone-bold" {...props}></Icon>
<style>
:global(.hnba5kd6n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km2_vvbqp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sg1q03b0n) {
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
}

:global(.ycftzzhuq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_cql0b5h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 15V8H21v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zgowxqjxj) {
  d: path("M15.5 15V8H21v7");
}

</style>
