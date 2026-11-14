<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pb47dvfao"/><path class="q2j62qnjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:achievement-hidden" {...props}></Icon>
<style>
:global(.pb47dvfao) {
  d: path("M5.5 15a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm4-5.75L7 2.5m7.5 6.75L17 2.5");
}

:global(.q2j62qnjb) {
  d: path("M10 13.25a2 2 0 1 1 2 2V16m0 2.5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
