<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5j-_fbnq"/><path class="k_-bicc8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dry-dock" {...props}></Icon>
<style>
:global(.b5j-_fbnq) {
  d: path("M3 4.5v15h18v-15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_-bicc8z) {
  d: path("M6 8h12l-2 7.5H8Zm4 7.5v4m4-4v4");
}

</style>
