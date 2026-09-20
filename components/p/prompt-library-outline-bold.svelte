<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="d-jukx5fx"/><path class="v72_3xj6k"/><path class="nlfm7tnix"/><path class="pmuiqo95v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prompt-library-outline-bold" {...props}></Icon>
<style>
:global(.d-jukx5fx) {
  d: path("M8 4v13");
}

:global(.nlfm7tnix) {
  d: path("M18 4v13");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v72_3xj6k) {
  d: path("M13 4v13");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
