<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ua36z6mem"/><circle class="h2g8fpd8t"/><path class="f1d-q_w_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:planet-transit" {...props}></Icon>
<style>
:global(.f1d-q_w_m) {
  d: path("M2.75 17.75h6l1.5 2.25h3.5l1.5-2.25h6");
}

:global(.h2g8fpd8t) {
  cx: 14px;
  cy: 9.5px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ua36z6mem) {
  cx: 12px;
  cy: 9px;
  r: 6.25px;
}

</style>
