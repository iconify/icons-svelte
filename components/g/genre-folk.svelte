<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxnv0nbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-folk" {...props}></Icon>
<style>
:global(.cxnv0nbrj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m5-13.5h1A1.5 1.5 0 0 1 14 4a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 4a1.5 1.5 0 0 1 1.5-1.5m.5 3v14m-2-2h4");
}

</style>
