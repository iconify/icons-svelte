<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i9zfb7b6u"/><path class="bsl4e65ev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:onion-dome" {...props}></Icon>
<style>
:global(.bsl4e65ev) {
  d: path("M10.5 21.5V19a1.5 1.5 0 0 1 3 0v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9zfb7b6u) {
  d: path("M10.5 11.5c-6.5-2-6-5.5 1.5-9c7.5 3.5 8 7 1.5 9Zm-.5 0h4a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 13a1.5 1.5 0 0 1 1.5-1.5m-4.5 3h13v7h-13Z");
}

</style>
