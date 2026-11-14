<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oshe5tbko"/><path class="w-7ocq19w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:picture-frame-wall" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oshe5tbko) {
  d: path("M6.5 6h11A3.5 3.5 0 0 1 21 9.5v8a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-8A3.5 3.5 0 0 1 6.5 6m2 0L12 2.75L15.5 6");
}

:global(.w-7ocq19w) {
  d: path("m3 18l6-5.5l5 5l2.5-2.25L21 19m-6.75-8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
