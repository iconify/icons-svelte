<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uk0rveqaj"/><path class="fgsu10bod"/><path class="maut9lbea"/><path class="mpg95hbwb"/><path class="ipv0cebdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diversity-mmr-outline-bold" {...props}></Icon>
<style>
:global(.fgsu10bod) {
  d: path("M7 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ipv0cebdm) {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.maut9lbea) {
  d: path("M4 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mpg95hbwb) {
  d: path("M15 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
