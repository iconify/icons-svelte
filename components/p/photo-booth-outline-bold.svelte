<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uk66x15py"/><path class="guo-qbwvt"/><path class="q686vz2zk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:photo-booth-outline-bold" {...props}></Icon>
<style>
:global(.guo-qbwvt) {
  d: path("M8 3v13c0 2 4 2 4 0V3");
}

:global(.q686vz2zk) {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uk66x15py) {
  d: path("M4 3v18h16V3Z");
}

</style>
