<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ur2rsfb9v"/><path class="s1-t1vpmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-mask-sheet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1-t1vpmq) {
  d: path("M7.25 10a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0m6 0a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0m-2.5 5.5h2.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 13.25 18h-2.5a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25");
}

:global(.ur2rsfb9v) {
  d: path("M4.5 12a7.5 9.5 0 1 0 15 0a7.5 9.5 0 1 0-15 0");
}

</style>
