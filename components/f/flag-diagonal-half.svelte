<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d6foahutw"/><path class="q8r-gyb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flag-diagonal-half" {...props}></Icon>
<style>
:global(.d6foahutw) {
  d: path("M5 2.5v19m1.5-18h11A1.5 1.5 0 0 1 19 5v7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 12V5a1.5 1.5 0 0 1 1.5-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q8r-gyb-a) {
  fill: currentColor;
  d: path("M6.5 3.5h7.819a1.5 1.5 0 0 1 .872 2.721l-7.819 5.585A1.5 1.5 0 0 1 5 10.585V5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
