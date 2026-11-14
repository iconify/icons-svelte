<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r6idl0dsj"/><path class="wy0fr6btc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crypto-news" {...props}></Icon>
<style>
:global(.r6idl0dsj) {
  d: path("M4 20h15.5a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-12a2 2 0 0 0-2 2v12.5a1.5 1.5 0 0 1-3 0V10h3M9 8h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wy0fr6btc) {
  d: path("M8.25 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7.75-2h2.5m-2.5 4h2.5");
}

</style>
