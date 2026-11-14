<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i3lojuboe"/><path class="fu_r9cbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:location-manager" {...props}></Icon>
<style>
:global(.fu_r9cbcq) {
  d: path("m9.189 9.811l1.75-1.75a1.5 1.5 0 0 1 2.122 0l1.75 1.75a1.5 1.5 0 0 1 .439 1.06v1.379a1.5 1.5 0 0 1-1.5 1.5h-3.5a1.5 1.5 0 0 1-1.5-1.5v-1.379a1.5 1.5 0 0 1 .439-1.06");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3lojuboe) {
  d: path("M12 21.5c-4-4-7.5-7.5-7.5-12a7.5 7.5 0 0 1 15 0c0 4.5-3.5 8-7.5 12");
}

</style>
