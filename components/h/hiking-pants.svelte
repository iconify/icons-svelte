<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k1_er-brp"/><path class="iwsy61scj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hiking-pants" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwsy61scj) {
  d: path("M14.5 2.5q.25 4.5 4 5.5");
}

:global(.k1_er-brp) {
  d: path("M6 2.5h12l1.5 19H14L12 9l-2 12.5H4.5Z");
}

</style>
