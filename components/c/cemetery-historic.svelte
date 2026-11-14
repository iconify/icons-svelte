<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwys-_biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cemetery-historic" {...props}></Icon>
<style>
:global(.jwys-_biy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M3 20v-7.5a3 3 0 0 1 6 0V20m3 0V8.5a4.25 4.25 0 0 1 8.5 0V20M16.25 8.5v6m-1.5-4h3");
}

</style>
