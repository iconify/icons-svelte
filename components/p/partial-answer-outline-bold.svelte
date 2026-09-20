<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="ze9yihd5h"/><path class="k-jt90-vx"/><path class="b-73d8bgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:partial-answer-outline-bold" {...props}></Icon>
<style>
:global(.b-73d8bgy) {
  d: path("M16 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k-jt90-vx) {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u1mon9cdo) {
  d: path("M3 15h9");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.ze9yihd5h) {
  d: path("M6 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
