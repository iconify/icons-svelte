<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lu5th6b2m"/><path class="gq7tyut-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-lost-property" {...props}></Icon>
<style>
:global(.gq7tyut-x) {
  d: path("M10 13.5a2 2 0 1 1 2 2v.5m0 2.25h.01");
}

:global(.lu5th6b2m) {
  d: path("M2.5 3.5h19v4h-19Zm1.5 4h16v14H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
