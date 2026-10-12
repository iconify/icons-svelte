<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="btebm7bgg"/><path class="njqu9ybef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:no-littering" {...props}></Icon>
<style>
:global(.btebm7bgg) {
  width: 3.5px;
  height: 3.5px;
  x: 3px;
  y: 10px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.njqu9ybef) {
  d: path("M3 16.5h9m-8 0L5 21h5l1-4.5M3.75 3.75l16.5 16.5");
}

</style>
