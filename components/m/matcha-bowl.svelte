<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xaxr0cc_a"/><path class="y7cl5n_xv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:matcha-bowl" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xaxr0cc_a) {
  d: path("M2.5 5.5h19c0 6.5-4 11-9.5 11S2.5 12 2.5 5.5m6 13.75h7");
}

:global(.y7cl5n_xv) {
  d: path("M6 9q3-1.5 6 0t6 0");
}

</style>
