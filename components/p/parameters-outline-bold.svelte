<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gg9qhlhxo"/><path class="pa1ot6bmg"/><path class="g9_eu8bfj"/><path class="fsi7fbbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parameters-outline-bold" {...props}></Icon>
<style>
:global(.fsi7fbbnr) {
  d: path("M13.5 15h5");
}

:global(.g9_eu8bfj) {
  d: path("M5.5 9h5");
}

:global(.gg9qhlhxo) {
  d: path("M8 4v16");
}

:global(.pa1ot6bmg) {
  d: path("M16 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
