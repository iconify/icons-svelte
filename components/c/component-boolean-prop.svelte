<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s2cegh51x"/><path class="ezleplbmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:component-boolean-prop" {...props}></Icon>
<style>
:global(.ezleplbmu) {
  d: path("m16 9.5l2.5 2.5l-2.5 2.5l-2.5-2.5Z");
}

:global(.s2cegh51x) {
  d: path("M5.5 7h13a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
