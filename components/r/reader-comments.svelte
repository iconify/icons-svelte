<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j0vu13bvu"/><path class="bq6_oza6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reader-comments" {...props}></Icon>
<style>
:global(.bq6_oza6z) {
  d: path("M7 7.5V5a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2H16M6 11h6.5M6 14h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j0vu13bvu) {
  d: path("M2.5 9.5a2 2 0 0 1 2-2H14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8l-3.5 3v-3a2 2 0 0 1-2-2Z");
}

</style>
