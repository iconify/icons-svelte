<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_xu-_-2j"/><path class="ndj8bdcuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barista" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_xu-_-2j) {
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 21.5c0-4 3.25-7 7.5-7q.969.002 1.857.2");
}

:global(.ndj8bdcuq) {
  d: path("M7.25 21.5v-3.25h4.95m.05 1.15v2.1m2.75-6h5v3.75a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5Zm5 1a1.5 1.5 0 0 1 0 3");
}

</style>
