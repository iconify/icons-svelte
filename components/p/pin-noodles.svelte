<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zub5e6bnh"/><path class="nty362flz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-noodles" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nty362flz) {
  d: path("M7.5 15.5q2.25-1.5 4.5 0t4.5 0");
}

:global(.zub5e6bnh) {
  d: path("M3 11h18c0 5.25-4 9-9 9s-9-3.75-9-9m10.5 0l4-8m-1 8L21 4");
}

</style>
