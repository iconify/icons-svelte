<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rp-sq47ba"/><path class="q7q-85-2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:focus-group" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q7q-85-2w) {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.25 7.25q0-2.5 4.25-2.5t4.25 2.5");
}

:global(.rp-sq47ba) {
  d: path("M5.5 2.5h13A2.5 2.5 0 0 1 21 5v10a2.5 2.5 0 0 1-2.5 2.5h-8l-4 3.5v-3.5h-1A2.5 2.5 0 0 1 3 15V5a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
