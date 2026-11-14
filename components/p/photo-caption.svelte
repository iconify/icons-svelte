<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z0c4oru_b"/><path class="z9x8te4hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:photo-caption" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0c4oru_b) {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v5a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 11V6A3.5 3.5 0 0 1 7 2.5");
}

:global(.z9x8te4hu) {
  d: path("m7 11.5l3.25-3.25l3.25 3.25m3-5h.01M3.5 18h17m-17 3.5H14");
}

</style>
