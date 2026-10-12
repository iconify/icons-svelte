<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b0b4psukm"/><path class="o0ipnnbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pencil-ruler" {...props}></Icon>
<style>
:global(.b0b4psukm) {
  width: 6.5px;
  height: 18.5px;
  x: 3.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o0ipnnbid) {
  d: path("M3.25 6.5h2.5M3.25 10h3.5m-3.5 3.5h2.5M3.25 17h3.5m7.5-.5V4.75a2 2 0 0 1 2-2h1.5a2 2 0 0 1 2 2V16.5L17 21.25Zm0-9.75h5.5");
}

</style>
