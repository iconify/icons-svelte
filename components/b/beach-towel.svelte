<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ycdjlfbmq"/><path class="nk02l7_sl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beach-towel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nk02l7_sl) {
  d: path("M8.5 11.5h11.25q1.5 0 .8 1.32l-2.85 5.36q-.7 1.32-2.2 1.32H4.25q-1.5 0-.8-1.32l2.85-5.36Q7 11.5 8.5 11.5m3.25 0l-4.25 8m9-8l-4.25 8");
}

:global(.ycdjlfbmq) {
  cx: 6.5px;
  cy: 5.75px;
  r: 2.25px;
}

</style>
