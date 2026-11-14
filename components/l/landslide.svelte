<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d894yzp-x"/><path class="h52ad9wiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:landslide" {...props}></Icon>
<style>
:global(.d894yzp-x) {
  d: path("M2.5 20.5v-16H6l2.5 6c3.5 1 7.5 4.5 13 5.5v4.5Z");
}

:global(.h52ad9wiz) {
  d: path("m11.5 6l5.5 5.5m-3.5 0H17V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
