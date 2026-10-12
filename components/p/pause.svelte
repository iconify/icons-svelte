<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="psrh26ros"/><rect class="bwvftibxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pause" {...props}></Icon>
<style>
:global(.bwvftibxc) {
  width: 4.5px;
  height: 16.5px;
  x: 13.75px;
  y: 3.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.psrh26ros) {
  width: 4.5px;
  height: 16.5px;
  x: 5.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
