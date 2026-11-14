<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x95f6cc5w"/><path class="nb0nz450i"/><path class="z2org3m-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:house-flipping" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nb0nz450i) {
  d: path("M10 21.5V18h4v3.5M4 11a8 7.5 0 0 1 16 0");
}

:global(.x95f6cc5w) {
  d: path("m5.611 12.976l5.25-4.5a1.75 1.75 0 0 1 2.278 0l5.25 4.5A1.75 1.75 0 0 1 19 14.305v5.445a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 19.75v-5.445a1.75 1.75 0 0 1 .611-1.329");
}

:global(.z2org3m-a) {
  d: path("M18.25 9.25L20 11l1.75-1.75");
}

</style>
