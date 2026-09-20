<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tqteed1fm"/><path class="hqkel0bnd"/><path class="uaurn5bqf"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:canyon-outline-bold" {...props}></Icon>
<style>
:global(.hqkel0bnd) {
  d: path("M22 3h-6v18");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tqteed1fm) {
  d: path("M2 3h6v18");
}

:global(.uaurn5bqf) {
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
}

</style>
