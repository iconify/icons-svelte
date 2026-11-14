<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suf2nacue"/><path class="dal0q1bok"/><path class="lb2b-6j3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chemical-drum" {...props}></Icon>
<style>
:global(.dal0q1bok) {
  d: path("M5 4v16a7 1.5 0 0 0 14 0V4M5 8.25h14m-14 9.5h14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb2b-6j3c) {
  d: path("m13.061 11.811l.128.128a1.5 1.5 0 0 1 0 2.122l-.128.128a1.5 1.5 0 0 1-2.122 0l-.128-.128a1.5 1.5 0 0 1 0-2.122l.128-.128a1.5 1.5 0 0 1 2.122 0");
}

:global(.suf2nacue) {
  d: path("M5 4a7 1.5 0 1 0 14 0A7 1.5 0 1 0 5 4");
}

</style>
