<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eqoe0pbrn"/><path class="h6-e9cbrs"/><path class="e88jyphuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bed-shop" {...props}></Icon>
<style>
:global(.e88jyphuk) {
  d: path("M8 20.5v-5h4v5m3-5.5v6.75m0-4.5h6.5v4.5M15 20h6.5");
}

:global(.eqoe0pbrn) {
  d: path("m3 8.5l1.5-5h15l1.5 5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0Z");
}

:global(.h6-e9cbrs) {
  d: path("M5.25 10.75v9.75h6.95m6.55-6.05v-3.7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
