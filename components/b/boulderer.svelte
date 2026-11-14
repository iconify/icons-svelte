<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ynk537bhq"/><path class="bn95epr4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boulderer" {...props}></Icon>
<style>
:global(.bn95epr4s) {
  d: path("m10.75 8.5l-5 1.5l.5 5L10 17.75M6.25 15L4 19.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ynk537bhq) {
  d: path("M10 20.5V12c0-4.5 3-7.5 6.5-7.5c3 0 5 2.5 5 6.5v9.5Zm-7.25-15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
