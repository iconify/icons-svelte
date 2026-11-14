<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ho6fckb9m"/><path class="mei7f1bac"/><path class="ho3z_ncdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-disc" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ho3z_ncdn) {
  d: path("M15.25 10.25V12L17 13");
}

:global(.ho6fckb9m) {
  d: path("M6.875 4.5h10.25A4.375 4.375 0 0 1 21.5 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 15.125v-6.25A4.375 4.375 0 0 1 6.875 4.5M5.75 7.75v8.5");
}

:global(.mei7f1bac) {
  d: path("M5.75 7.75h.75a2.25 2.25 0 0 1 0 4.5h-.75m6-.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
