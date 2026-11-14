<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw49jcbqb"/><path class="q5n_mozqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:no-horn-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iw49jcbqb) {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0");
}

:global(.q5n_mozqk) {
  d: path("M5.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4-1H12l5-3v8l-5-3H9.25m-4-7.75l13.5 13.5");
}

</style>
