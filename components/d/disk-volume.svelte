<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="twazkm86z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:disk-volume" {...props}></Icon>
<style>
:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.twazkm86z) {
  d: path("M6.5 10.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm5.5 0h.01M7 18.75h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
