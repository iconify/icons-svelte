<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7vwa9y1y"/><path class="w0y_71b6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-long-press" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w0y_71b6m) {
  d: path("M6.24 13.25A5.5 5.5 0 1 1 16.5 10.5");
}

:global(.x7vwa9y1y) {
  d: path("M9.75 16v-5.5a1.25 1.25 0 0 1 2.5 0V14H14a2.5 2.5 0 0 1 2.5 2.5v.5a4.25 4.25 0 0 1-4.25 4.25h-.75a3.75 3.75 0 0 1-3.75-3.75V17a1 1 0 0 1 1-1Zm2.5-1.5v2.25");
}

</style>
