<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="b5citz2uj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bill-of-lading" {...props}></Icon>
<style>
:global(.b5citz2uj) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M9 6h.5A1.5 1.5 0 0 1 11 7.5V8a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 8v-.5A1.5 1.5 0 0 1 9 6m-1.5 7h9m-9 4h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_a5jubhp) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
