<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwnt4cbdg"/><path class="yy4vufhpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:confirmation-candle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwnt4cbdg) {
  d: path("M9.5 12.75V9a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v3.75m-5 2.5v6.25h5v-6.25M12 2.5c1.75 2 1.25 2.75 0 2.75s-1.75-.75 0-2.75");
}

:global(.yy4vufhpm) {
  d: path("m12 14l-6-3v6Zm0 0l6-3v6Z");
}

</style>
