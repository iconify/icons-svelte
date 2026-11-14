<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-ebwpoja"/><path class="cb477-0bc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-farm" {...props}></Icon>
<style>
:global(.cb477-0bc) {
  d: path("M6.25 12c2.5-3.75 7.25-3.75 9 0l2.5-2.25v4.5L15.25 12c-1.75 3.75-6.5 3.75-9 0m3.5-.25h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-ebwpoja) {
  d: path("M7 3.5h10A3.5 3.5 0 0 1 20.5 7v10a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17V7A3.5 3.5 0 0 1 7 3.5");
}

</style>
