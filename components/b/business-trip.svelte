<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ats88qb5k"/><path class="s-q4tibsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-trip" {...props}></Icon>
<style>
:global(.ats88qb5k) {
  d: path("M6 7h12v12.5H6Zm3.5 0V2.5h5V7");
}

:global(.s-q4tibsy) {
  d: path("M8 20.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
