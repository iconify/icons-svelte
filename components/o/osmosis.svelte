<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="in6wolo3y"/><path class="d-3cqzb-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:osmosis" {...props}></Icon>
<style>
:global(.d-3cqzb-s) {
  d: path("m15 12l2.5 2.5L15 17");
}

:global(.in6wolo3y) {
  d: path("M3.5 4v14a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V4M12 4v16M3.5 10H12m0-3h8.5m-14 7.5h11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
