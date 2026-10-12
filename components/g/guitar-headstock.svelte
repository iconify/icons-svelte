<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s4m_h4vil"/><circle class="rsnkvx63x"/><path class="j8ly7-y-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:guitar-headstock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8ly7-y-w) {
  d: path("m6.25 16.25l1.5 1.5");
}

:global(.rsnkvx63x) {
  cx: 10px;
  cy: 14px;
  r: 1.5px;
}

:global(.s4m_h4vil) {
  d: path("M13.96 14.63a5.25 5.25 0 1 1-4.59-4.59a3.75 3.75 0 1 1 4.59 4.59m5.82-11.12l.71.71q.53.53 0 1.06l-1.41 1.41q-.53.53-1.06 0l-.71-.71q-.53-.53 0-1.06l1.41-1.41q.53-.53 1.06 0m-6.03 6.74l4.1-4.1");
}

</style>
