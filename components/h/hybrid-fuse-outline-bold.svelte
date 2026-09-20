<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pr6npvbsh"/><path class="xxvssxb6x"/><path class="lqiw_3bos"/><path class="dhtq24lfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hybrid-fuse-outline-bold" {...props}></Icon>
<style>
:global(.dhtq24lfs) {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
}

:global(.lqiw_3bos) {
  d: path("M10 12h7");
}

:global(.pr6npvbsh) {
  d: path("m3 5 6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xxvssxb6x) {
  d: path("m3 19 6 -6");
}

</style>
