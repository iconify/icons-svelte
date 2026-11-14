<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q1stf9too"/><path class="ranxnmeyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cowboy-boot" {...props}></Icon>
<style>
:global(.q1stf9too) {
  d: path("M4 2.5h10l-1.5 10c1.5 2 5.5 3 7.5 6.25l-1.25.75H10.5l-1 2h-4L6 13Z");
}

:global(.ranxnmeyd) {
  d: path("M4.75 6.5Q9 9 13.25 6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
