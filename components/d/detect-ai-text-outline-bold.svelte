<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="iwea3dacr"/><path class="nffgw9y5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detect-ai-text-outline-bold" {...props}></Icon>
<style>
:global(.iwea3dacr) {
  d: path("M12.5 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nffgw9y5n) {
  d: path("m19.5 19 2 2");
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

</style>
