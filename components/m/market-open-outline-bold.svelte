<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ja-d7-b4a"/><path class="ic_pehd5a"/><path class="gyu499fcn"/><path class="k4y331wag"/><path class="xdvtlk8qz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:market-open-outline-bold" {...props}></Icon>
<style>
:global(.gyu499fcn) {
  d: path("M12 6v2.5");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.ja-d7-b4a) {
  d: path("M6 17a6 6 0 0 1 12 0");
}

:global(.k4y331wag) {
  d: path("m4.5 9.5 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xdvtlk8qz) {
  d: path("m19.5 9.5 -2 2");
}

</style>
