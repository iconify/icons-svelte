<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="hac_4ac9i"/><path class="amw1sioot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:graph-results" {...props}></Icon>
<style>
:global(.amw1sioot) {
  d: path("M15.5 8H19v3.5");
}

:global(.hac_4ac9i) {
  d: path("m7 16.5l4-4.5l3 2.5L19 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

</style>
