<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djojk-bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fencing-parry" {...props}></Icon>
<style>
:global(.djojk-bgf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 20.5l17-17m0 17l-17-17m2 10.5l4.5 4.5m8.5-4.5L14 18.5");
}

</style>
