<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_pnjqb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mu" {...props}></Icon>
<style>
:global(.z_pnjqb2p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8v13.5m0-7a4 4 0 0 0 8 0m0-6.5v8.75c0 1.5 1 2.25 2.5 2");
}

</style>
