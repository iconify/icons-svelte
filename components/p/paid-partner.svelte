<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zit0atbsk"/><path class="sbues1b-t"/><circle class="f4x3joxaq"/><path class="grpe3ebbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:paid-partner" {...props}></Icon>
<style>
:global(.f4x3joxaq) {
  cx: 18px;
  cy: 17.25px;
  r: 3.25px;
}

:global(.grpe3ebbt) {
  d: path("M18 15.75v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sbues1b-t) {
  d: path("M4.5 20.25H12a.75.75 0 0 0 .75-.75c0-3-2.1-5-4.5-5s-4.5 2-4.5 5a.75.75 0 0 0 .75.75M14 3.75a3.25 3.25 0 0 1 0 6.5");
}

:global(.zit0atbsk) {
  cx: 8.25px;
  cy: 9px;
  r: 3px;
}

</style>
