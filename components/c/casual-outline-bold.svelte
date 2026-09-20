<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o_ssmh9ez"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/><path class="it66gbbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:casual-outline-bold" {...props}></Icon>
<style>
:global(.dy-bj6bwq) {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.it66gbbyl) {
  d: path("M8 14c1.5 2.5 6.5 2.5 8 0");
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
