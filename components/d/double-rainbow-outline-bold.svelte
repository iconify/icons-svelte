<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ydpucsi6v"/><path class="azjtlhb3x"/><path class="no90vc3pu"/><path class="wk7jmzmpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:double-rainbow-outline-bold" {...props}></Icon>
<style>
:global(.azjtlhb3x) {
  d: path("M4 18a8 8 0 0 1 16 0");
}

:global(.no90vc3pu) {
  d: path("M7 18a5 5 0 0 1 10 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wk7jmzmpf) {
  d: path("M9 18a3 3 0 0 1 6 0");
}

:global(.ydpucsi6v) {
  d: path("M2 18a10 10 0 0 1 20 0");
}

</style>
