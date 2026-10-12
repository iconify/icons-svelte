<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d0i767bps"/><path class="bc473n1re"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:notepad" {...props}></Icon>
<style>
:global(.bc473n1re) {
  d: path("M8 11h8m-8 3.5h8M8 18h5M8 2.75v4m4-4v4m4-4v4");
}

:global(.d0i767bps) {
  width: 14.5px;
  height: 16.5px;
  x: 4.75px;
  y: 4.75px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
