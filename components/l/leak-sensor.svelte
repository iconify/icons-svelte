<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kz0udu9yp"/><path class="hmv4nkl8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leak-sensor" {...props}></Icon>
<style>
:global(.hmv4nkl8r) {
  d: path("M4.5 15v3a7.5 2.25 0 0 0 15 0v-3m-17 5.25h19M12 2.5q3 3 3 4.5a3 3 0 0 1-6 0q0-1.5 3-4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kz0udu9yp) {
  d: path("M4.5 15a7.5 2.25 0 1 0 15 0a7.5 2.25 0 1 0-15 0");
}

</style>
