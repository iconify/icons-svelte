<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i4garqvdt"/><path class="q5udl2jej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loan-term-loan" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4garqvdt) {
  d: path("M3 17.5h18M3 15v5m18-5v5M6.5 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.q5udl2jej) {
  d: path("M13.5 7.25c0-.75-.75-1-1.5-1c-1 0-1.5.5-1.5 1.25c0 1.5 3 1 3 3c0 .75-.5 1.25-1.5 1.25c-.75 0-1.5-.5-1.5-1m1.5-5.5v1m0 5.5v1");
}

</style>
