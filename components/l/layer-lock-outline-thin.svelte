<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eywlytabr"/><path class="jgql0jyyx"/><path class="ypui4ib8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:layer-lock-outline-thin" {...props}></Icon>
<style>
:global(.eywlytabr) {
  d: path("M4 3.5A1.5 1.5 0 0 1 5.5 2h13A1.5 1.5 0 0 1 20 3.5 1.5 1.5 0 0 1 18.5 5h-13A1.5 1.5 0 0 1 4 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgql0jyyx) {
  d: path("M8.5 15a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.ypui4ib8n) {
  d: path("M9.5 13a2.5 2.5 0 0 1 5 0");
}

</style>
