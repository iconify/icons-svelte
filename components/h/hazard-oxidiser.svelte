<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrkh46bbk"/><path class="xt9ywwthk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hazard-oxidiser" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rrkh46bbk) {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.xt9ywwthk) {
  d: path("M8 13.5c-1.5-3 .5-5.5 1.5-8q2.25 2.25 2.25 4.5C12.5 8 13.5 5.5 14 2.5c3 3 3.5 7.5 2 11");
}

</style>
