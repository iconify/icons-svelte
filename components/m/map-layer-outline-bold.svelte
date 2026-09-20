<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kk4vcs1ji"/><path class="gumem2bkh"/><path class="ov7kkt0lo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-layer-outline-bold" {...props}></Icon>
<style>
:global(.gumem2bkh) {
  d: path("m6 13 6 6 6 -6");
}

:global(.kk4vcs1ji) {
  d: path("m12 2 7 7 -7 7 -7 -7Z");
}

:global(.ov7kkt0lo) {
  d: path("m8 17 4 4 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
