<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="virtrhrph"/><path class="mzdha_obf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-vent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzdha_obf) {
  d: path("M7 7h10M7 10h10m-9.25 7.25q-1 1 0 2t0 2m4.25-4q-1 1 0 2t0 2m4.25-4q-1 1 0 2t0 2");
}

:global(.virtrhrph) {
  width: 17.5px;
  height: 11.5px;
  x: 3.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
