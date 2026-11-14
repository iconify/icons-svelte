<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le5pnccev"/><path class="slbpnol2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bank-book" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.le5pnccev) {
  d: path("M3 19V5a2.5 2.5 0 0 1 2.5-2.5H13v19H5.5A2.5 2.5 0 0 1 3 19");
}

:global(.slbpnol2f) {
  d: path("M3 19a2.5 2.5 0 0 1 2.5-2.5H13m2.5 1l3-2.75l3 2.75m-4.5 0v4m3-4v4m-4.5 0h6");
}

</style>
