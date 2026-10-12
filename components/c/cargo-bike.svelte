<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcet26bht"/><rect class="zkwwv3eif"/><circle class="bwfh0gvgc"/><circle class="osdeuxbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cargo-bike" {...props}></Icon>
<style>
:global(.bwfh0gvgc) {
  cx: 5.75px;
  cy: 18px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lcet26bht) {
  d: path("M7.43 15.82L10 12.5h3.25m-3.25 0l-.75-3M8 9.5h2.5m7.75 4v3");
}

:global(.osdeuxbhk) {
  cx: 18.25px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.zkwwv3eif) {
  width: 7.5px;
  height: 5.25px;
  x: 13.25px;
  y: 8.25px;
  rx: 1px;
}

</style>
