<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xqk_x5mcn"/><path class="y875pzbpu"/><path class="zm2dyvb-o"/><path class="i4vwidv3a"/><path class="dqhx63ndl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bee-outline-bold" {...props}></Icon>
<style>
:global(.dqhx63ndl) {
  d: path("M16 10c3 -4 6 -1 5 2s-4 2 -5 -2");
}

:global(.i4vwidv3a) {
  d: path("M8 10c-3 -4 -6 -1 -5 2s4 2 5 -2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xqk_x5mcn) {
  d: path("M8 9a4 4 0 0 1 8 0v8a4 4 0 0 1 -8 0Z");
}

:global(.y875pzbpu) {
  d: path("M8.5 12h7");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

</style>
