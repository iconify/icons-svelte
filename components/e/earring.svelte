<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ko01rhb0b"/><circle class="jb8wwbf-o"/><path class="jv4lm2xpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:earring" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jb8wwbf-o) {
  cx: 12px;
  cy: 10px;
  r: 1.25px;
}

:global(.jv4lm2xpl) {
  d: path("M12 11.25c3 3 4 4.5 4 6a4 4 0 0 1-8 0c0-1.5 1-3 4-6");
}

:global(.ko01rhb0b) {
  d: path("M9.75 5.25a2.25 2.25 0 1 1 4.5 0C14.25 6.75 12 7 12 8.75");
}

</style>
