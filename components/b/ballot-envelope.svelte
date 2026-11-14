<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xukv3-b9o"/><path class="ujfsvl36y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ballot-envelope" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ujfsvl36y) {
  d: path("M2.75 12L12 17l9.25-5M9.75 6.25L11.5 8l3-3");
}

:global(.xukv3-b9o) {
  d: path("M6 11h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-3.5A3.5 3.5 0 0 1 6 11m0 0V2.5h12V11");
}

</style>
