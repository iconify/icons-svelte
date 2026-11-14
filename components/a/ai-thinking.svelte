<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yuq-jrx4t"/><path class="aejlqiboo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ai-thinking" {...props}></Icon>
<style>
:global(.aejlqiboo) {
  d: path("M7.75 12.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yuq-jrx4t) {
  d: path("M7 18.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Z");
}

</style>
