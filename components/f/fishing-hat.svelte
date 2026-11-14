<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0tdkjb-n"/><path class="yhxk3_bfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fishing-hat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0tdkjb-n) {
  d: path("M6.5 14L8 6a2 2 0 0 1 2-1.5h4A2 2 0 0 1 16 6l1.5 8");
}

:global(.yhxk3_bfq) {
  d: path("M2.5 15.5a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0m5-5h9");
}

</style>
