<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oyxz1j97b"/><path class="bwea0cckg"/><path class="zumwcq4gc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:archway" {...props}></Icon>
<style>
:global(.bwea0cckg) {
  d: path("M8 21v-7a4 4 0 0 1 8 0v7");
}

:global(.oyxz1j97b) {
  d: path("M3 3.5h18V21H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zumwcq4gc) {
  d: path("M10.25 6.5h3.5L13 10h-2Z");
}

</style>
