<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qfn-j9wac"/><rect class="dyccw0bfy"/><path class="i7xqrebyh"/><path class="jh-99p2rf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pakistan-crescent-flag-star" {...props}></Icon>
<style>
:global(.dyccw0bfy) {
  width: 15.75px;
  height: 12.5px;
  x: 5.5px;
  y: 4px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7xqrebyh) {
  d: path("M9 4v12.5m7.5-9.37a3.5 3.5 0 1 0 0 6.24a3.25 3.25 0 0 1 0-6.24");
}

:global(.jh-99p2rf) {
  d: path("m18 7.63l.21.47q.1.23.35.26l.52.05q.25.03.06.19l-.39.35q-.18.17-.13.41l.11.51q.05.24-.16.12l-.45-.26q-.22-.13-.44 0l-.45.26q-.21.12-.16-.12l.11-.51q.05-.24-.13-.41l-.39-.35q-.19-.16.06-.19l.52-.05q.25-.03.35-.26l.21-.47q.1-.23.2 0");
}

:global(.qfn-j9wac) {
  d: path("M3 2.75v18.5");
}

</style>
