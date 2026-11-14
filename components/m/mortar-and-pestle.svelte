<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqhsuyi2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mortar-and-pestle" {...props}></Icon>
<style>
:global(.eqhsuyi2w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h16c0 4.5-3.5 8-8 8s-8-3.5-8-8m6-7.5L14 9");
}

</style>
