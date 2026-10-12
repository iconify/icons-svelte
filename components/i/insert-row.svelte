<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="j544a9bhb"/><path class="o8xkc8_wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:insert-row" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j544a9bhb) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

:global(.o8xkc8_wx) {
  d: path("M2.75 8.25h18.5M9 8.25v5.5m6-5.5v5.5m-3 2.75v4.75m-2.375-2.375h4.75");
}

</style>
