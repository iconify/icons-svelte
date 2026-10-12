<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w1ghlpbud"/><path class="b_zhkbf3c"/><rect class="u74et4b5e"/><path class="ll3_6zypj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:photo-album" {...props}></Icon>
<style>
:global(.b_zhkbf3c) {
  d: path("M7.25 2.75v18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ll3_6zypj) {
  d: path("M10.25 17h6.5");
}

:global(.u74et4b5e) {
  width: 6.5px;
  height: 6px;
  x: 10.25px;
  y: 7.25px;
  rx: 1px;
}

:global(.w1ghlpbud) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
