<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mdm1iobsd"/><path class="d9-7lf7lk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mass-spectrometer" {...props}></Icon>
<style>
:global(.d9-7lf7lk) {
  d: path("M11.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdm1iobsd) {
  d: path("M9.5 6H18a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 18H9.5A3.5 3.5 0 0 1 6 14.5v-5A3.5 3.5 0 0 1 9.5 6m-7 6H6");
}

</style>
