<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="af-8092tf"/><path class="bvrvnub3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:co2-jet" {...props}></Icon>
<style>
:global(.af-8092tf) {
  d: path("M7 10za3.5 3.5 0 0 1 3.5 3.5V18A3.5 3.5 0 0 1 7 21.5A3.5 3.5 0 0 1 3.5 18v-4.5A3.5 3.5 0 0 1 7 10m-1.5 0V6.75h6.25m-3.25 0V10");
}

:global(.bvrvnub3a) {
  d: path("M14 9a2.25 2.25 0 0 1 0-4.5a2.75 2.75 0 0 1 5.25 0a2.25 2.25 0 0 1 0 4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
