<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z11fxxb2g"/><path class="r5uhpub3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delivery-vehicle-ev" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r5uhpub3m) {
  d: path("M5.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10.5 8l-2 4h3l-2 3");
}

:global(.z11fxxb2g) {
  d: path("M3 17V8a2 2 0 0 1 2-2h9l5 5h2v6Z");
}

</style>
