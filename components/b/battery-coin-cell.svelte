<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nsyxnlb_e"/><path class="h0--x8cea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:battery-coin-cell" {...props}></Icon>
<style>
:global(.h0--x8cea) {
  d: path("M2.5 9v5.5a9.5 5.5 0 0 0 19 0V9M12 7v4m-2-2h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nsyxnlb_e) {
  d: path("M2.5 9a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0");
}

</style>
