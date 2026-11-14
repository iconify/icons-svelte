<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="invd1db9g"/><path class="re8qlrrbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camera-outdoor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.invd1db9g) {
  d: path("M19.5 5.5H8.75a3.75 3.75 0 0 0 0 7.5H19.5");
}

:global(.re8qlrrbr) {
  d: path("M17.5 9.25a2 3.75 0 1 0 4 0a2 3.75 0 1 0-4 0M6 2.75h15.5M11.5 13v5.25h-6M4 15za1.5 1.5 0 0 1 1.5 1.5V20A1.5 1.5 0 0 1 4 21.5A1.5 1.5 0 0 1 2.5 20v-3.5A1.5 1.5 0 0 1 4 15");
}

</style>
