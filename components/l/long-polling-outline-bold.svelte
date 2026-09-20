<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:long-polling-outline-bold" {...props}></Icon>
<style>
:global(.bxa1b1bso) {
  d: path("M6 5v14");
}

:global(.fr472ib_x) {
  d: path("m13 16 3 3 3 -3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x7g1r9bby) {
  d: path("M16 5v14");
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
