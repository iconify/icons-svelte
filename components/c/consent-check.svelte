<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p7r4cbb7y"/><path class="oaqids5ed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:consent-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oaqids5ed) {
  d: path("m7.5 12.5l3 3l6-7");
}

:global(.p7r4cbb7y) {
  d: path("M10.5 3.5h3a7 7 0 0 1 7 7v3a7 7 0 0 1-7 7h-3a7 7 0 0 1-7-7v-3a7 7 0 0 1 7-7");
}

</style>
