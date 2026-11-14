<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv13qmbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:high-heel" {...props}></Icon>
<style>
:global(.dv13qmbnk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 19h4c4 0 7-7.5 11-8h2V5h-1.5c-2.5 0-5 9-10.5 9H5.5q-3 0-3 3q0 2 1.5 2m16.5-8v9.5");
}

</style>
