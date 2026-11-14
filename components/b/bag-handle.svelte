<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5l9cgcsq"/><path class="n44_ztbcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bag-handle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n44_ztbcm) {
  d: path("M8.5 15v-4a3.5 3.5 0 0 1 7 0v4M5.25 15h3.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 5.25 15m10 0h3.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 15.25 15M7 16.75h.01m9.99 0h.01");
}

:global(.s5l9cgcsq) {
  d: path("M5.5 15v-4a6.5 6.5 0 0 1 13 0v4");
}

</style>
