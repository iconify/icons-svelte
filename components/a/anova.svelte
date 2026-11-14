<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h96z1abos"/><path class="l2bd0lb6o"/><path class="ynp6q9bkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anova" {...props}></Icon>
<style>
:global(.h96z1abos) {
  d: path("M2.5 19.5C5.25 19.5 6.5 6 8 6s2.75 13.5 5.5 13.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2bd0lb6o) {
  d: path("M6.5 19.5c2.75 0 4-9.5 5.5-9.5s2.75 9.5 5.5 9.5");
}

:global(.ynp6q9bkm) {
  d: path("M10.5 19.5c2.75 0 4-15 5.5-15s2.75 15 5.5 15m-19 1h19");
}

</style>
