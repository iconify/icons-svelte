<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="whl9nbc_l"/><path class="q-delcftb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bubble-tea-sealed" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q-delcftb) {
  d: path("M13 2.5zA1.5 1.5 0 0 1 14.5 4v5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 11.5 9V4A1.5 1.5 0 0 1 13 2.5M9.5 18.75h.01m4.99 0h.01M12 15.5h.01");
}

:global(.whl9nbc_l) {
  d: path("m5.5 7.5l1.5 14h10l1.5-14M4 7.5h16");
}

</style>
