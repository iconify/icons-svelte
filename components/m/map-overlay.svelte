<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqtl5rb5a"/><path class="d_slbjb_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-overlay" {...props}></Icon>
<style>
:global(.d_slbjb_t) {
  d: path("M12 8.5h6a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 8.5 18v-6A3.5 3.5 0 0 1 12 8.5");
}

:global(.fqtl5rb5a) {
  d: path("M6 2.5h6A3.5 3.5 0 0 1 15.5 6v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12V6A3.5 3.5 0 0 1 6 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
