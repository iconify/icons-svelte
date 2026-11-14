<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj4dymbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-zipline" {...props}></Icon>
<style>
:global(.rj4dymbyw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2 3l20 5m-9.25 3a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M10 5v6.5l1 5l5 3.5m-5-3.5l-1.5 5");
}

</style>
