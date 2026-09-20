<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="awo9bn4mw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-video-outline-bold" {...props}></Icon>
<style>
:global(.awo9bn4mw) {
  d: path("M16 8v8l4 -4Z");
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
