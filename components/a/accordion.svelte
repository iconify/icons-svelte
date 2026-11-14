<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ndnygt_up"/><path class="ga8xxqb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:accordion" {...props}></Icon>
<style>
:global(.ga8xxqb2l) {
  d: path("m15.5 5.25l1.5 1.5l1.5-1.5m-3 9.75l1.5-1.5l1.5 1.5M5 20.25h10");
}

:global(.ndnygt_up) {
  d: path("M2.5 3.25h19v5.5h-19Zm0 8.25h19V17h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
