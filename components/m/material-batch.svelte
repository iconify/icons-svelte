<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uy51d2b0b"/><path class="tn_sjwlmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:material-batch" {...props}></Icon>
<style>
:global(.tn_sjwlmm) {
  d: path("M7.5 9H12v4.5H7.5ZM12 9h4.5v4.5H12ZM9.75 4.5h4.5V9h-4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uy51d2b0b) {
  d: path("m3.5 10l2 10h13l2-10");
}

</style>
