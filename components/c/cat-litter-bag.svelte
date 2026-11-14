<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skyc11b_j"/><path class="vecl8hbxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cat-litter-bag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.skyc11b_j) {
  d: path("M7.423 3h9.154a2.625 2.625 0 0 1 2.616 2.416l1.08 13.5a2.625 2.625 0 0 1-2.616 2.834H6.343a2.625 2.625 0 0 1-2.616-2.834l1.08-13.5A2.625 2.625 0 0 1 7.423 3M5 6.25h14");
}

:global(.vecl8hbxi) {
  d: path("m7.75 9l2.75 3h3l2.75-3v5.75a4.25 4.25 0 0 1-8.5 0Zm2.75 5.75h.01m2.99 0h.01");
}

</style>
