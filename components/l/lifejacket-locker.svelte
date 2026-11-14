<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npjdwld4r"/><path class="ye8qu3m9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lifejacket-locker" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.npjdwld4r) {
  d: path("M14 2.5H3v19h11zL20 5v14l-6 2.5");
}

:global(.ye8qu3m9f) {
  d: path("m6 8.5l1.5-2l1 3l1-3l1.5 2v9H6Z");
}

</style>
