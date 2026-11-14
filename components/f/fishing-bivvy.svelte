<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n3n7k4rmk"/><path class="m91odid_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fishing-bivvy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m91odid_d) {
  d: path("M8.5 19.5c0-5 1.5-7.5 3.5-7.5s3.5 2.5 3.5 7.5");
}

:global(.n3n7k4rmk) {
  d: path("M3.5 19.5c0-9 4-14.5 8.5-14.5s8.5 5.5 8.5 14.5M2 19.5h20");
}

</style>
