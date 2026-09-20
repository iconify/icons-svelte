<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpfjab_r"/><path class="o7p-7ib_v"/><path class="cavvnbbud"/><path class="zraij0c3r"/><path class="tsfcwwbwb"/><path class="b0hkzgbgd"/><path class="wuk2mlziz"/><path class="kq98nmbqp"/><path class="rxr8gqf5x"/><path class="m_a9oxi_o"/><path class="y4a8ig_7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:build-matrix-duotone-bold" {...props}></Icon>
<style>
:global(.b0hkzgbgd) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.cavvnbbud) {
  fill: currentColor;
  d: path("M13.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kq98nmbqp) {
  d: path("M8.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m_a9oxi_o) {
  d: path("M8.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nzpfjab_r) {
  fill: currentColor;
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o7p-7ib_v) {
  fill: currentColor;
  d: path("M8.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rxr8gqf5x) {
  d: path("M13.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tsfcwwbwb) {
  fill: currentColor;
  d: path("M13.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.y4a8ig_7t) {
  d: path("M13.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zraij0c3r) {
  fill: currentColor;
  d: path("M8.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
