<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ulcz-u44f"/><path class="zdqjytzem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fishing-net-landing" {...props}></Icon>
<style>
:global(.ulcz-u44f) {
  d: path("M3 7a6.5 3.5 0 1 0 13 0A6.5 3.5 0 1 0 3 7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdqjytzem) {
  d: path("M3 7.5C3.5 14 6.5 18 9.5 18s6-4 6.5-10.5m-.75 2.5L21 20.5m-11.5-10v7m-5-4.5h10");
}

</style>
