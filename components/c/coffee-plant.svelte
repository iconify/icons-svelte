<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="alw6hccxn"/><circle class="mhd4ugusn"/><circle class="f6q4dkbbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coffee-plant" {...props}></Icon>
<style>
:global(.alw6hccxn) {
  d: path("M3 9.75q9-1.5 18 0m-13-.6v5.35m8-5.35v7.35M6 9.33V6m8 3.04V5.75M6 6q4 1.44 4.75-2.75Q6.75 1.81 6 6m8-.25q3.89 1.63 4.75-2.5q-3.89-1.63-4.75 2.5");
}

:global(.f6q4dkbbu) {
  cx: 16px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mhd4ugusn) {
  cx: 8px;
  cy: 16.75px;
  r: 2.25px;
}

</style>
