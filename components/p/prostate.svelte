<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bp8v15b4h"/><path class="b2sy9c4co"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:prostate" {...props}></Icon>
<style>
:global(.b2sy9c4co) {
  fill: currentColor;
  d: path("M7.5 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.bp8v15b4h) {
  d: path("M3.5 14a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m11.25-4.75L20.5 3.5m-5 0h5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
