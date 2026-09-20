<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx2y4tasg"/><path class="y62iljmfo"/><path class="l9z5uubso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nappy-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l9z5uubso) {
  d: path("M15 8V5h4v3");
}

:global(.y62iljmfo) {
  d: path("M5 8V5h4v3");
}

:global(.yx2y4tasg) {
  d: path("M5 8h14l-7 7Z");
}

</style>
