<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hfqtzjb6y"/><path class="r-6yyzbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hill-pair" {...props}></Icon>
<style>
:global(.hfqtzjb6y) {
  d: path("M2.5 18q7-18 14 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r-6yyzbtz) {
  d: path("M13 11.25C15 6 20 4 21.5 18m-19 0h19");
}

</style>
