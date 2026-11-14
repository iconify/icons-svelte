<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="in6wolo3y"/><path class="d-3cqzb-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:osmosis" {...props}></Icon>
<style>
:global(.d-3cqzb-s) {
  d: path("m15 12l2.5 2.5L15 17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.in6wolo3y) {
  d: path("M3.5 4v14a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V4M12 4v16M3.5 10H12m0-3h8.5m-14 7.5h11");
}

</style>
