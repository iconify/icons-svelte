<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bqau9xh1a"/><path class="eovkbbbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:regulation-book" {...props}></Icon>
<style>
:global(.bqau9xh1a) {
  width: 13.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

:global(.eovkbbbhf) {
  d: path("M7.25 2.75v18.5M10 7h4.5m2.75-2h2.5a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1h-2.5m0 2.5h2.5a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1h-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
