<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b-v_5_bcl"/><path class="f4jjwhbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mug" {...props}></Icon>
<style>
:global(.b-v_5_bcl) {
  width: 12.5px;
  height: 16.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2.5px;
}

:global(.f4jjwhbfu) {
  d: path("M16.25 8.75h1.5a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-1.5M10 16l-2.1-2.1a1.3 1.3 0 0 1 2.1-1.6a1.3 1.3 0 0 1 2.1 1.6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
