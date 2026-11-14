<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq1kxu9ay"/><path class="x_n5bmicb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:confidence-monitor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sq1kxu9ay) {
  d: path("M7.191 4h9.618a2.625 2.625 0 0 1 2.583 2.155l1.045 5.75A2.625 2.625 0 0 1 17.855 15H6.145a2.625 2.625 0 0 1-2.582-3.095l1.045-5.75A2.625 2.625 0 0 1 7.191 4M3 20.5h18");
}

:global(.x_n5bmicb) {
  d: path("M8.947 6.75h6.106a1.5 1.5 0 0 1 1.462 1.168l.569 2.5a1.5 1.5 0 0 1-1.463 1.832H8.379a1.5 1.5 0 0 1-1.463-1.832l.569-2.5A1.5 1.5 0 0 1 8.947 6.75M9.5 15L8 20.5m6.5-5.5l1.5 5.5");
}

</style>
