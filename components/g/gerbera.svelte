<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ee7_vjjhi"/><path class="jblk5ftrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gerbera" {...props}></Icon>
<style>
:global(.ee7_vjjhi) {
  d: path("m12 2l1.25 3.25l2.75-2l-.75 3.5h3.5L16 9l2.75 2.25h-3.5l.75 3.5l-2.75-2L12 16l-1.25-3.25l-2.75 2l.75-3.5h-3.5L8 9L5.25 6.75h3.5L8 3.25l2.75 2Zm0 14v5.5");
}

:global(.jblk5ftrc) {
  d: path("M10.75 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
