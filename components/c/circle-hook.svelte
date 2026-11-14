<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5br__bzy"/><path class="i4b1r2bjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circle-hook" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4b1r2bjy) {
  d: path("M8 7v8a5 5 0 1 0 3.25-4.75l-.25 3");
}

:global(.x5br__bzy) {
  d: path("M6 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
