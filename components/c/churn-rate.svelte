<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja6da9bnf"/><path class="jf_mep8lq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:churn-rate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja6da9bnf) {
  d: path("M4.428 5h10.144a1.75 1.75 0 0 1 1.742 1.919l-1.161 12a1.75 1.75 0 0 1-1.742 1.581H5.589a1.75 1.75 0 0 1-1.742-1.581l-1.161-12A1.75 1.75 0 0 1 4.428 5M3.5 9.5h12");
}

:global(.jf_mep8lq) {
  fill: currentColor;
  d: path("M19 13c.75 1 1.25 1.75 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.5.5-1.25 1.25-2.25m1.25 5c.75 1 1.25 1.75 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.5.5-1.25 1.25-2.25");
}

</style>
