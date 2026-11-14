<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9gx__b9j"/><path class="s0a-8-58i"/><path class="rqpz5n_0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pest-snail" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r9gx__b9j) {
  d: path("M3.5 11a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.rqpz5n_0o) {
  d: path("M10 11h3.5A3.5 3.5 0 1 1 10 7.5m11 3L19 7m2 3.5l.75-3.5M2.5 20.5H12");
}

:global(.s0a-8-58i) {
  d: path("M2.5 17.5h16A2.5 2.5 0 0 0 21 15v-4.5");
}

</style>
