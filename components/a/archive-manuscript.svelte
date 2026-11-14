<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4tcibcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:archive-manuscript" {...props}></Icon>
<style>
:global(.dj4tcibcw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 15h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2m.5-11v11m12-11v11M9 10h6m-6 4h4.5");
}

</style>
