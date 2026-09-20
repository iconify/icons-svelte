<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk66_ohsf"/><path class="qfm0f643r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:experiment-duotone-thin" {...props}></Icon>
<style>
:global(.hk66_ohsf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qfm0f643r) {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3");
}

</style>
