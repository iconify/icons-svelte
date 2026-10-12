<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d02scy2nh"/><rect class="xb8_egb3s"/><path class="y942ybcdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:audio-jack" {...props}></Icon>
<style>
:global(.d02scy2nh) {
  d: path("M10.5 9.75v-5.5a1.5 1.5 0 0 1 3 0v5.5Zm0-3h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xb8_egb3s) {
  width: 6.5px;
  height: 7.5px;
  x: 8.75px;
  y: 9.75px;
  rx: 1.5px;
}

:global(.y942ybcdk) {
  d: path("M12 17.25v4");
}

</style>
