<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfbiai0yf"/><path class="svi45obbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:daisy" {...props}></Icon>
<style>
:global(.bfbiai0yf) {
  d: path("M16.75 11.25A2 2 0 0 1 14 14a2 2 0 0 1-4 0a2 2 0 0 1-2.75-2.75a2 2 0 0 1 0-4A2 2 0 0 1 10 4.5a2 2 0 0 1 4 0a2 2 0 0 1 2.75 2.75a2 2 0 0 1 0 4ZM12 16v5.5");
}

:global(.svi45obbu) {
  d: path("M10 9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 11.25q4.5 0 6-3q-4-.5-6 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
