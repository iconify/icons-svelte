<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="po47_2bjy"/><path class="oz614acod"/><path class="iqy6wdsji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dance-floor-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iqy6wdsji) {
  d: path("M8 16h7v5H8Z");
}

:global(.oz614acod) {
  d: path("M13 7h7v6h-7Z");
}

:global(.po47_2bjy) {
  d: path("M3 7h7v6H3Z");
}

</style>
