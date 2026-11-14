<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yshkx3bnp"/><path class="gk4ff154h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:equity-split" {...props}></Icon>
<style>
:global(.gk4ff154h) {
  d: path("M13.25 10.75v-8a8 8 0 0 1 8 8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yshkx3bnp) {
  d: path("M10.5 13.5v-8a8 8 0 1 0 8 8Z");
}

</style>
