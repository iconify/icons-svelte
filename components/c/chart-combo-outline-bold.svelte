<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pbz4y6llk"/><path class="xqz890wro"/><path class="ejtyvbbdg"/><path class="rkhcgsbdl"/><path class="t4vjq-bqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-combo-outline-bold" {...props}></Icon>
<style>
:global(.ejtyvbbdg) {
  d: path("M17 15v4");
}

:global(.pbz4y6llk) {
  d: path("M5 13v6");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t4vjq-bqk) {
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
}

:global(.xqz890wro) {
  d: path("M11 12v7");
}

</style>
