<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c4ddk56my"/><rect class="xpm_8sffh"/><path class="n_ahpacqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:macaron" {...props}></Icon>
<style>
:global(.c4ddk56my) {
  d: path("M3.5 9.25c0-2.25 3.8-4 8.5-4s8.5 1.75 8.5 4a.75.75 0 0 1-.75.75H4.25a.75.75 0 0 1-.75-.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_ahpacqh) {
  d: path("M3.5 14.75a.75.75 0 0 1 .75-.75h15.5a.75.75 0 0 1 .75.75c0 2.25-3.8 4-8.5 4s-8.5-1.75-8.5-4");
}

:global(.xpm_8sffh) {
  width: 13.5px;
  height: 4px;
  x: 5.25px;
  y: 10px;
  rx: 0.75px;
}

</style>
