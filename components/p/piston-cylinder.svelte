<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-xvdcc7d"/><path class="xsx3-g7lm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:piston-cylinder" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-xvdcc7d) {
  d: path("M5 5v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V5");
}

:global(.xsx3-g7lm) {
  d: path("M6.5 11h11a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 12.5A1.5 1.5 0 0 1 6.5 11m2-8.5h7m-3.5 0V11");
}

</style>
