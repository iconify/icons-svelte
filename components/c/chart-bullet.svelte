<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="km9suhz3y"/><rect class="kdqip3bmm"/><path class="b6h2a3bwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-bullet" {...props}></Icon>
<style>
:global(.b6h2a3bwy) {
  d: path("M17.5 5v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdqip3bmm) {
  width: 9.5px;
  height: 3px;
  x: 5px;
  y: 10.5px;
  rx: 1px;
}

:global(.km9suhz3y) {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 8px;
  rx: 1.5px;
}

</style>
