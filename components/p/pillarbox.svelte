<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="aywjn1ddl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pillarbox" {...props}></Icon>
<style>
:global(.aywjn1ddl) {
  fill: currentColor;
  d: path("M5.5 5.5h-1a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2h1Zm13 0h1a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-1Z");
}

:global(.mhuvow97a) {
  d: path("M2.5 5.5h19v13h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
