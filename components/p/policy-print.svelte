<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r_0wl0jcl"/><path class="q-haombgm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:policy-print" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q-haombgm) {
  d: path("M7 14h10v6.5H7Z");
}

:global(.r_0wl0jcl) {
  d: path("M7.5 9.5h9A3.5 3.5 0 0 1 20 13v1a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 14v-1a3.5 3.5 0 0 1 3.5-3.5m-.5 0v-6h10v6");
}

</style>
