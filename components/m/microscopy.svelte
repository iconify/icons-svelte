<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nf3amcb1y"/><path class="ljoa3-byl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:microscopy" {...props}></Icon>
<style>
:global(.ljoa3-byl) {
  d: path("M16.5 21c3.5-4 3-10-3.25-12.75M8.5 15.5h7");
}

:global(.nf3amcb1y) {
  d: path("m6.268 4.17l3.464-2l5 8.66l-3.464 2ZM5 21h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
