<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vn_j8nq7w"/><path class="gqhkf0wts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plaster-kids" {...props}></Icon>
<style>
:global(.gqhkf0wts) {
  d: path("M8.5 7.5c-1 2.5-1 6.5 0 9m7-9c1 2.5 1 6.5 0 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vn_j8nq7w) {
  d: path("M7 7.5h10a4.5 4.5 0 0 1 4.5 4.5a4.5 4.5 0 0 1-4.5 4.5H7A4.5 4.5 0 0 1 2.5 12A4.5 4.5 0 0 1 7 7.5");
}

</style>
