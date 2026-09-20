<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jet-bridge-outline-thin" {...props}></Icon>
<style>
:global(.ah-zd_bma) {
  d: path("M13 9v7");
}

:global(.czysiurpc) {
  d: path("M3 9h15v7H3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i699y-pkg) {
  d: path("M21 6v13");
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.yg08zkbcc) {
  d: path("M8 9v7");
}

</style>
