<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wux2vybcj"/><path class="u8j490b7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:carbon-capture" {...props}></Icon>
<style>
:global(.u8j490b7n) {
  d: path("m15.25 6.25l2 2l2-2m-6.25 8h8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wux2vybcj) {
  d: path("m3 21l1.25-8h3.5L9 21Zm10-10h8.5v10H13Zm-7-.75q-1.5-2 0-4m3-.75C11.5 3 16.5 3 17.25 8.25");
}

</style>
