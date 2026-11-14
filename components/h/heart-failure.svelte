<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ylvxi9d8v"/><path class="kewsbackd"/><path class="i_wa5ybab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heart-failure" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_wa5ybab) {
  d: path("M19 19.5h2.75v-2.75");
}

:global(.kewsbackd) {
  d: path("m10 9l-1.25 2L11 12l-1.25 2m4.5 1L17 18l2-1.75l2.5 3");
}

:global(.ylvxi9d8v) {
  d: path("M11.569 15.905C10.654 16.594 10 17 10 17s-7.25-4.5-7.25-9c0-2.25 1.75-4 3.75-4C8 4 9.25 5 10 6c.75-1 2-2 3.5-2c2 0 3.75 1.75 3.75 4c0 1.533-.842 3.067-1.952 4.422");
}

</style>
