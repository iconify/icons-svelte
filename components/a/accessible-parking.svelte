<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etw475bob"/><path class="yu1r-pdvb"/><path class="f1bbb0bma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:accessible-parking" {...props}></Icon>
<style>
:global(.etw475bob) {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3M11 7h.01");
}

:global(.f1bbb0bma) {
  d: path("M10.5 11.25a3.5 3.5 0 1 1-3.5 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yu1r-pdvb) {
  d: path("M11 9.75v4.5h3.75l1.75 3.5");
}

</style>
