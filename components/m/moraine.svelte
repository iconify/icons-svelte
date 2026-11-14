<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y2x36_bmf"/><path class="s9kr0qb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:moraine" {...props}></Icon>
<style>
:global(.s9kr0qb9x) {
  d: path("M7.5 12.5L9 7l4-1.5l1.5 5.5l-4 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y2x36_bmf) {
  d: path("m3 18.5l1-4l3.5-2l3 1.5v4.5Zm7.5 0V14l4-3l4.5 1l2 6.5Z");
}

</style>
