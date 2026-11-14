<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ms0j1kbzx"/><path class="syuw_3pbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rear-defrost" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ms0j1kbzx) {
  d: path("M7.375 3.5h9.25A4.375 4.375 0 0 1 21 7.875v2.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 10.125v-2.25A4.375 4.375 0 0 1 7.375 3.5");
}

:global(.syuw_3pbr) {
  d: path("M8 8c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4m4-13c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4m4-13c-1 1.5 1 3 0 4.5s1 3 0 4.5s1 3 0 4");
}

</style>
