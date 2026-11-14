<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nh9tfripy"/><path class="hbdwe-b5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dark-beer" {...props}></Icon>
<style>
:global(.hbdwe-b5w) {
  d: path("M5.75 7.5q1.75 2 3.25 0t3 0t3 0t3.25 0");
}

:global(.nh9tfripy) {
  d: path("M5.5 3h13L17 21H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
