<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rd2u59dlh"/><path class="e7bx2db1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dryer-lint-filter" {...props}></Icon>
<style>
:global(.e7bx2db1k) {
  d: path("M10 8q1-1.25 2 0t2 0");
}

:global(.rd2u59dlh) {
  d: path("M3 4h18l-7 8.5V19l-4 2.5v-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
