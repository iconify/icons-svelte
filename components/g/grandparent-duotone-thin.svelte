<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmwrvubhz"/><path class="c7kjqqh8k"/><path class="jgp2jybfi"/><path class="f1a0i3x1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grandparent-duotone-thin" {...props}></Icon>
<style>
:global(.c7kjqqh8k) {
  d: path("M7 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.f1a0i3x1x) {
  d: path("M18 9v12");
}

:global(.hmwrvubhz) {
  fill: currentColor;
  d: path("M7 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgp2jybfi) {
  d: path("M5.5 17a4.5 4.5 0 0 1 9 0");
}

</style>
