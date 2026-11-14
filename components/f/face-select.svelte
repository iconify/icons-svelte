<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_xzsccbw"/><path class="vwqnabcex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:face-select" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_xzsccbw) {
  d: path("M4 20V10h10v10Zm0-10l6-6h10v10l-6 6m0-10l6-6");
}

:global(.vwqnabcex) {
  fill: currentColor;
  d: path("M4 10h10v10H4Z");
}

</style>
