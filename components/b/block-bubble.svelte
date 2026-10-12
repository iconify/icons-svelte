<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="v2el3udsi"/><path class="eqq6hubwb"/><circle class="hk4_ptb-x"/><path class="ypu6wob8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:block-bubble" {...props}></Icon>
<style>
:global(.eqq6hubwb) {
  d: path("M3.25 20.75c0-3.5 2.8-6.25 6.25-6.25c.9 0 1.75.17 2.5.5");
}

:global(.hk4_ptb-x) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v2el3udsi) {
  cx: 9.5px;
  cy: 7.5px;
  r: 3.75px;
}

:global(.ypu6wob8i) {
  d: path("m14.85 14.85l5.3 5.3");
}

</style>
