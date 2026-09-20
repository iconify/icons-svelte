<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7epg_b9a"/><path class="dfd9p4b0j"/><path class="yp6zlzbcu"/><path class="ufjf60bpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:footpath-outline-thin" {...props}></Icon>
<style>
:global(.dfd9p4b0j) {
  d: path("M7 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o7epg_b9a) {
  d: path("M6.5 7a2.5 2.5 0 0 1 5 0v4a2.5 2.5 0 0 1 -5 0Z");
}

:global(.ufjf60bpr) {
  d: path("M13 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yp6zlzbcu) {
  d: path("M12.5 14a2.5 2.5 0 0 1 5 0v4a2.5 2.5 0 0 1 -5 0Z");
}

</style>
