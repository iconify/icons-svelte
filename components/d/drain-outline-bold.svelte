<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zpvo49dam"/><path class="l3yb7ybjz"/><path class="mdp-r2mfo"/><path class="mbzvimb-r"/><path class="tjvfebbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drain-outline-bold" {...props}></Icon>
<style>
:global(.l3yb7ybjz) {
  d: path("M2 9h6");
}

:global(.mbzvimb-r) {
  d: path("M12 14v5");
}

:global(.mdp-r2mfo) {
  d: path("M16 9h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tjvfebbkf) {
  d: path("M9.5 16.5 12 19l2.5 -2.5");
}

:global(.zpvo49dam) {
  d: path("M8 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
