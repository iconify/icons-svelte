<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gurg9_4oi"/><path class="hznq92a2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colour-replace" {...props}></Icon>
<style>
:global(.gurg9_4oi) {
  fill: currentColor;
  d: path("M2.5 2.5h8v8h-8Z");
}

:global(.hznq92a2q) {
  d: path("M13.5 13.5h8v8h-8Zm.5-9h2.5a3 3 0 0 1 3 3v3m-2-2l2 2l2-2M10 19.5H7.5a3 3 0 0 1-3-3v-3m-2 2l2-2l2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
