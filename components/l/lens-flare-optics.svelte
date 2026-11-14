<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rs1wsibwn"/><path class="ezlaigbou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lens-flare-optics" {...props}></Icon>
<style>
:global(.ezlaigbou) {
  d: path("M6 14.5A3.5 3.5 0 0 1 9.5 11m7-3.5l3-3M19 12l2.5-.75M12 5l.75-2.5");
}

:global(.rs1wsibwn) {
  d: path("M2.5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
