<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy3seac0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:downtown" {...props}></Icon>
<style>
:global(.jy3seac0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5V10H9v10.5m0 0v-16h6v16m0 0V12h5.5v8.5m-18 0h19");
}

</style>
