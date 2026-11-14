<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_ji0cbtm"/><path class="tkcj85b3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mail-question" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_ji0cbtm) {
  d: path("M4.5 4h13a2 2 0 0 1 2 2v5.5H14l-3 5v.5H4.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2");
}

:global(.tkcj85b3d) {
  d: path("m6 7.5l5 3.5l5-3.5m.25 9c0-1 .75-1.75 1.75-1.75s1.75.75 1.75 1.75c0 1.25-1.75 1.25-1.75 2.5m0 2.25h.01");
}

</style>
