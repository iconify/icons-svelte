<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyxtg4bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grand-piano" {...props}></Icon>
<style>
:global(.vyxtg4bjc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5a2 2 0 0 1 2-2h4c1.5 0 2 2 3 4.5s7 4 7 8.5v3a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm0 12.5h16m-12 0V21m4-3.5V21m4-3.5V21");
}

</style>
