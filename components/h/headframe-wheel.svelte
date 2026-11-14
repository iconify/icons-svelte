<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kaw7ibbdn"/><path class="j_k5utbyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:headframe-wheel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_k5utbyv) {
  d: path("m5.5 21.5l6.5-14l6.5 14M7 7.5h10m0 0v14");
}

:global(.kaw7ibbdn) {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
