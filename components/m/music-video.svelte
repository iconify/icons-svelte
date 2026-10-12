<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yymvhuctj"/><circle class="xe95m5bil"/><circle class="uit8fi3go"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:music-video" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uit8fi3go) {
  cx: 17.75px;
  cy: 15.25px;
  r: 2.75px;
}

:global(.xe95m5bil) {
  cx: 6.25px;
  cy: 17.25px;
  r: 2.75px;
}

:global(.yymvhuctj) {
  d: path("M9 17.25V6.35a1 1 0 0 1 .8-.98l9.5-1.9a1 1 0 0 1 1.2.98v10.8");
}

</style>
