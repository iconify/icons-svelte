<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gfyw8vbbf"/><path class="d-v-f28sf"/><path class="c-xj8zban"/><path class="q1jaj6b2n"/><path class="chx4f6b7j"/><path class="y69n27oio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-graph-outline-bold" {...props}></Icon>
<style>
:global(.c-xj8zban) {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.chx4f6b7j) {
  d: path("m14 15 2 2");
}

:global(.d-v-f28sf) {
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gfyw8vbbf) {
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
}

:global(.q1jaj6b2n) {
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y69n27oio) {
  d: path("m20 15 -2 2");
}

</style>
