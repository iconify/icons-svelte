<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzlgfc6ta"/><path class="ukspgxbul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:red-eye" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ukspgxbul) {
  d: path("M9 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01m-7.26 0L6.5 11l.75 1m12-.5L17.5 11l-.75-1M18 13.75l-1.5.25");
}

:global(.wzlgfc6ta) {
  d: path("M2.5 11.5c2.5-4 6-6 9.5-6s7 2 9.5 6c-2.5 4-6 6-9.5 6s-7-2-9.5-6");
}

</style>
