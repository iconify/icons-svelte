<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tg3-9613w"/><path class="c674zoe4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-print" {...props}></Icon>
<style>
:global(.c674zoe4n) {
  d: path("m7.5 10.5l3-1l3 1l3-1v7l-3 1l-3-1l-3 1Zm3-1v7m3-6v7");
}

:global(.tg3-9613w) {
  d: path("M6.5 2.5H14L19.5 8v11.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
