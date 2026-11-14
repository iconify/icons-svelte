<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8l8xobzy"/><path class="oqh1jzweq"/><path class="dlox2lbtc"/><path class="ekdsuac_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pylon-sign" {...props}></Icon>
<style>
:global(.c8l8xobzy) {
  d: path("M8.5 2.5h7l1.5 19H7Zm-6 19h19");
}

:global(.dlox2lbtc) {
  fill: currentColor;
  d: path("m12 5.25l.441 1.143l1.223.066l-.951.773l.316 1.184L12 7.75l-1.029.666l.316-1.184l-.951-.773l1.223-.066Z");
}

:global(.ekdsuac_o) {
  d: path("M10 13h4m-4 3.5h4");
}

:global(.oqh1jzweq) {
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
