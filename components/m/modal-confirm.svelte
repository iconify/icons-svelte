<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z0wll3bik"/><path class="ga-i7-3tq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:modal-confirm" {...props}></Icon>
<style>
:global(.ga-i7-3tq) {
  d: path("m9 10l2 2l4-4m-8.5 8.5h3.75m3.5 0h3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0wll3bik) {
  d: path("M7.375 3.5h9.25A4.375 4.375 0 0 1 21 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 16.125v-8.25A4.375 4.375 0 0 1 7.375 3.5");
}

</style>
