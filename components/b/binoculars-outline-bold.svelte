<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f0lu7bcgk"/><path class="mzz93ed1z"/><path class="y0y0ccsoe"/><path class="lmdddlr1e"/><path class="p7w3a5bcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:binoculars-outline-bold" {...props}></Icon>
<style>
:global(.f0lu7bcgk) {
  d: path("M3 8v11h7V8Z");
}

:global(.lmdddlr1e) {
  d: path("M4 5h5");
}

:global(.mzz93ed1z) {
  d: path("M14 8v11h7V8Z");
}

:global(.p7w3a5bcn) {
  d: path("M15 5h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
