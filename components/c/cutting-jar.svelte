<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-yyxnb8f"/><path class="vjxttwbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cutting-jar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjxttwbsz) {
  d: path("M11.5 19c0-5 0-9 .5-12.5m0 1c0-3 2.5-5 5.5-5c0 3-2.5 5-5.5 5m-5.5 8h11");
}

:global(.w-yyxnb8f) {
  d: path("M5.5 9h1v10.5a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2V9h1");
}

</style>
