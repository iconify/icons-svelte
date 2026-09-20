<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="ngnirel9c"/><path class="f_g4z7roy"/><path class="qii79lbir"/><path class="nfwlsobue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:golden-set-outline-bold" {...props}></Icon>
<style>
:global(.f_g4z7roy) {
  d: path("m16 8 2 2 3 -3");
}

:global(.nfwlsobue) {
  d: path("m16 13 2 2 3 -3");
}

:global(.ngnirel9c) {
  d: path("M6 9h8");
}

:global(.qii79lbir) {
  d: path("M6 14h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
