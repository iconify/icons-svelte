<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jj13gfhhu"/><rect class="zpyd0tbkc"/><rect class="kw0yqvblm"/><path class="l_5owzbnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:griddle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jj13gfhhu) {
  width: 5px;
  height: 3px;
  x: 5.5px;
  y: 11.5px;
  rx: 1.5px;
}

:global(.kw0yqvblm) {
  width: 15px;
  height: 4px;
  x: 4.5px;
  y: 14.5px;
  rx: 1.5px;
}

:global(.l_5owzbnb) {
  d: path("M4.5 16.5H2.75m16.75 0h1.75");
}

:global(.zpyd0tbkc) {
  width: 5px;
  height: 3px;
  x: 13.5px;
  y: 11.5px;
  rx: 1.5px;
}

</style>
