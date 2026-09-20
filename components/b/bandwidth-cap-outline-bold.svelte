<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xf07dvr8m"/><path class="ml3aqbbkk"/><path class="rw2cw9fuy"/><path class="pq2hynbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bandwidth-cap-outline-bold" {...props}></Icon>
<style>
:global(.ml3aqbbkk) {
  d: path("M4 8v12");
}

:global(.pq2hynbuc) {
  d: path("m6 18 4 -4 3 3 6 -6");
}

:global(.rw2cw9fuy) {
  d: path("M4 20h17");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

</style>
