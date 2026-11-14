<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zg_875wcp"/><path class="l18l-ccti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:points-history" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l18l-ccti) {
  d: path("M4.5 4v4h4m3.5.5v4l3 2");
}

:global(.zg_875wcp) {
  d: path("M4.5 12A7.5 7.5 0 1 0 7 6.5");
}

</style>
