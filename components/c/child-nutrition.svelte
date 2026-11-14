<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-1tojbak"/><path class="cx9eeebfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:child-nutrition" {...props}></Icon>
<style>
:global(.cx9eeebfu) {
  d: path("M5.25 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m4.5 0V7.5m0 4.5l3.75 2.5M9.75 12L6 14.5M18.75 6a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0m1.5 2.5v12");
}

:global(.d-1tojbak) {
  d: path("M2.25 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
