<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f8zh8l_by"/><path class="no9neyd8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:farm-fleet" {...props}></Icon>
<style>
:global(.f8zh8l_by) {
  d: path("M2.5 15.5v-5H12v-4a1 1 0 0 1 1-1h3.5l3 4.5h1a1 1 0 0 1 1 1v4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.no9neyd8o) {
  d: path("M5.5 6h2a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 7.5 10.5h-2a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 5.5 6M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
