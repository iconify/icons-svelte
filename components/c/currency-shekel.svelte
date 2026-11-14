<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phr86grdn"/><path class="lidid4bmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-shekel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lidid4bmz) {
  d: path("M18.5 4.5v15h-6A3.5 3.5 0 0 1 9 16V9");
}

:global(.phr86grdn) {
  d: path("M5.5 19.5v-15h6A3.5 3.5 0 0 1 15 8v7");
}

</style>
