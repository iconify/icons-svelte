<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-59hn8hc"/><path class="hf_gtezns"/><path class="kyboc-b7u"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jitter-duotone-thin" {...props}></Icon>
<style>
:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-59hn8hc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kyboc-b7u) {
  d: path("m3 15 5 -5 2 2 4 -4 3 3 4 -4");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
