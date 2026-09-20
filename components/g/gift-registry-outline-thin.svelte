<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojk--hbsz"/><path class="j8dldre2z"/><path class="cfd43lbgp"/><path class="szshe-6ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gift-registry-outline-thin" {...props}></Icon>
<style>
:global(.cfd43lbgp) {
  d: path("M7 13h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8dldre2z) {
  d: path("M9 9a2 2 0 1 1 3 0 2 2 0 1 1 3 0");
}

:global(.ojk--hbsz) {
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.szshe-6ah) {
  d: path("M7 17h10");
}

</style>
