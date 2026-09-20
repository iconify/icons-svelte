<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jfhg8zbol"/><path class="m1u_gbo_m"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gauge-outline-bold" {...props}></Icon>
<style>
:global(.jfhg8zbol) {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

:global(.m1u_gbo_m) {
  d: path("m12 17 -5 -5");
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
