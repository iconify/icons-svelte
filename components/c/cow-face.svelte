<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tmyl-pbfy"/><path class="om28nobxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cow-face" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.om28nobxn) {
  d: path("M6.5 17.5a5.5 3.5 0 1 0 11 0a5.5 3.5 0 1 0-11 0m3.5 0h.01m3.99 0h.01");
}

:global(.tmyl-pbfy) {
  d: path("M8 15L7 7c0-1.25.75-2 2-2h6c1.25 0 2 .75 2 2l-1 8M4 2.5C4.5 4 6 5 8.5 5m7 0c2.5 0 4-1 4.5-2.5m-13 6C5.5 8 3.5 8.5 2.5 10c1.5 1 3.5 1 4.75.5m9.75-2c1.5-.5 3.5 0 4.5 1.5c-1.5 1-3.5 1-4.75.5");
}

</style>
