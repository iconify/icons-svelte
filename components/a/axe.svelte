<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fror7elkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:axe" {...props}></Icon>
<style>
:global(.fror7elkb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75v18.5m0-17h5.5c4.25 0 7.75 3 8.75 7.75a1.25 1.25 0 0 1-1.25 1.5h-13Z");
}

</style>
