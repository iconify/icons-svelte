<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="t5aoeccqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drawer-top" {...props}></Icon>
<style>
:global(.o0uxpabcc) {
  d: path("M2.5 3.5h19v17h-19Z");
}

:global(.t5aoeccqt) {
  d: path("M8.5 3.5V6A1.5 1.5 0 0 0 10 7.5h4A1.5 1.5 0 0 0 15.5 6V3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
