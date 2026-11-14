<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kf09lihqj"/><path class="p9tq0zrti"/><path class="u-ec9j55s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kayak-roll" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kf09lihqj) {
  d: path("M5.75 12c2.75 3 9.75 3 12.5 0c-2.75-2-9.75-2-12.5 0");
}

:global(.p9tq0zrti) {
  d: path("M7.5 19.75a9 9 0 1 1 9 0");
}

:global(.u-ec9j55s) {
  d: path("m17.25 16.75l-.75 3l3 .75");
}

</style>
