<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="g8ej4ylky"/><path class="i73rcdbbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:copyright-document" {...props}></Icon>
<style>
:global(.g8ej4ylky) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-11.75 6a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i73rcdbbe) {
  d: path("M13 13.5a1.5 1.5 0 1 0 0 2");
}

:global(.w_a5jubhp) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
