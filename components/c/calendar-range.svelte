<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcw5wwb5t"/><path class="i0lw9851c"/><path class="tz7pjxbkb"/><path class="yioqrbhqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-range" {...props}></Icon>
<style>
:global(.i0lw9851c) {
  fill: currentColor;
  d: path("M6.25 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.qcw5wwb5t) {
  d: path("M3.5 4.5h17V21h-17Zm4.5-2v4m8-4v4m-12.5 3h17");
}

:global(.tz7pjxbkb) {
  d: path("M7.25 15.25h9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yioqrbhqs) {
  fill: currentColor;
  d: path("M15.75 15.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
