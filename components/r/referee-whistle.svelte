<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbzduus-g"/><path class="i72xm7ypi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:referee-whistle" {...props}></Icon>
<style>
:global(.hbzduus-g) {
  d: path("M9 6.5h11A1.5 1.5 0 0 1 21.5 8v1a1.5 1.5 0 0 1-1.5 1.5h-5.75A5.5 5.5 0 1 1 9 6.5Z");
}

:global(.i72xm7ypi) {
  d: path("M7 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
