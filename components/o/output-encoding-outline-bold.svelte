<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymp2b4b6u"/><path class="jx89umbuc"/><path class="zr0lwnjnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:output-encoding-outline-bold" {...props}></Icon>
<style>
:global(.jx89umbuc) {
  d: path("M9.5 8.5 7 11l2.5 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

:global(.zr0lwnjnt) {
  d: path("M14.5 8.5 17 11l-2.5 2.5");
}

</style>
