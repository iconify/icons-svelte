<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="feh5q_b1s"/><path class="wgzf3kbdp"/><path class="w7dz13y2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cpr-outline-bold" {...props}></Icon>
<style>
:global(.feh5q_b1s) {
  d: path("M5 14a3.5 3.5 0 0 1 7 0 3.5 3.5 0 0 1 7 0l-7 7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w7dz13y2v) {
  d: path("m8 2 4 4 4 -4");
}

:global(.wgzf3kbdp) {
  d: path("m8 6 4 4 4 -4");
}

</style>
