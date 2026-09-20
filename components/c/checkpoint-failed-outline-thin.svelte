<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftqzjnb8u"/><path class="tkvxdludj"/><path class="k58vknb8e"/><path class="a1go-lhea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-failed-outline-thin" {...props}></Icon>
<style>
:global(.a1go-lhea) {
  d: path("m21 13 -5 5");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k58vknb8e) {
  d: path("m16 13 5 5");
}

:global(.tkvxdludj) {
  d: path("M6 3h9l-3 3 3 3H6");
}

</style>
