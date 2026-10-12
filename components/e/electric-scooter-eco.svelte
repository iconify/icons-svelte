<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wboxv9bpl"/><circle class="xs_28x-yu"/><path class="xqk0nkbqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:electric-scooter-eco" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wboxv9bpl) {
  cx: 5.5px;
  cy: 18.5px;
  r: 2.75px;
}

:global(.xqk0nkbqc) {
  d: path("M8.25 18.5h7.5M18 15.75l-2.25-12h2.5M8.75 14c0-3 1.75-4.75 5-4.75c0 3-1.75 4.75-5 4.75");
}

:global(.xs_28x-yu) {
  cx: 18.5px;
  cy: 18.5px;
  r: 2.75px;
}

</style>
