<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q2j9owbjj"/><rect class="j8tytbbff"/><path class="y_amm84ko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:conditioner" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8tytbbff) {
  width: 8.5px;
  height: 12.75px;
  x: 3.75px;
  y: 8.5px;
  rx: 2.5px;
}

:global(.q2j9owbjj) {
  width: 5px;
  height: 2.75px;
  x: 5.5px;
  y: 2.75px;
  rx: 1px;
}

:global(.y_amm84ko) {
  d: path("M17.75 4.75c2.5 2.5 2.5 4.5 0 7s-2.5 4.5 0 7");
}

</style>
