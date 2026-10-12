<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ppkmu3b3c"/><path class="syl1gfckl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:phone-landscape" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ppkmu3b3c) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 2.5px;
}

:global(.syl1gfckl) {
  d: path("M18.25 10.75v2.5");
}

</style>
