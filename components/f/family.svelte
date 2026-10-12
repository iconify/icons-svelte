<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t6ozvr6zj"/><circle class="z1qpurb8m"/><path class="qnrk4qblw"/><circle class="yjztigbem"/><path class="ayw990bzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:family" {...props}></Icon>
<style>
:global(.ayw990bzt) {
  d: path("M10.75 20.5v-1.75a1.25 1.25 0 0 1 2.5 0v1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qnrk4qblw) {
  d: path("M2.75 20.5V17a2.5 2.5 0 0 1 5 0v3.5m8.5 0V17a2.5 2.5 0 0 1 5 0v3.5");
}

:global(.t6ozvr6zj) {
  cx: 5.25px;
  cy: 9px;
  r: 2.5px;
}

:global(.yjztigbem) {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

:global(.z1qpurb8m) {
  cx: 18.75px;
  cy: 9px;
  r: 2.5px;
}

</style>
