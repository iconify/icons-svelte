<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ka4-q8b6z"/><path class="tc9oxcc5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ophthalmoscope" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka4-q8b6z) {
  d: path("M12 12za2.5 2.5 0 0 1 2.5 2.5V19a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 19v-4.5A2.5 2.5 0 0 1 12 12M7.5 6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

:global(.tc9oxcc5b) {
  d: path("M10.75 6.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-1.25 9h5");
}

</style>
