<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwcb6qb0j"/><path class="hm15quftp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:electric-plane" {...props}></Icon>
<style>
:global(.cwcb6qb0j) {
  d: path("M2.5 16h16.25a2.75 2.75 0 0 0 0-5.5H12l-3.5-8h-6Zm7.5 0l-2.5 4.5h2.75l4-4.5");
}

:global(.hm15quftp) {
  d: path("M6.5 4.75L5 7.25h2.75L6.25 9.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
