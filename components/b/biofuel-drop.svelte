<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5zxrdbnw"/><path class="uan-t6v5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:biofuel-drop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n5zxrdbnw) {
  d: path("M12 2.5c3 4 6.5 7.5 6.5 12a6.5 6.5 0 0 1-13 0c0-4.5 3.5-8 6.5-12");
}

:global(.uan-t6v5z) {
  d: path("M9 17.25C9 14 11 12 15 12c0 3.25-2 5.25-6 5.25");
}

</style>
