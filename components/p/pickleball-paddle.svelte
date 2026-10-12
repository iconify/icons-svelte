<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="az4-0fr-v"/><rect class="cn86-iudz"/><circle class="bf9_qabtn"/><path class="xaehkvbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pickleball-paddle" {...props}></Icon>
<style>
:global(.az4-0fr-v) {
  width: 9.5px;
  height: 11.5px;
  x: 3.25px;
  y: 2.75px;
  rx: 2px;
}

:global(.bf9_qabtn) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

:global(.cn86-iudz) {
  width: 3px;
  height: 7px;
  x: 6.5px;
  y: 14.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xaehkvbgh) {
  d: path("M16.65 18.35h.01m1.69-1.7h.01");
}

</style>
