<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1gttpbzo"/><path class="ko18k2bkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-down-right" {...props}></Icon>
<style>
:global(.b1gttpbzo) {
  d: path("M4.5 4.5V11A3.5 3.5 0 0 0 8 14.5h11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ko18k2bkg) {
  d: path("m14.5 9.5l5 5l-5 5");
}

</style>
