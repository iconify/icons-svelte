<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy_pab_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lift-wind-hold" {...props}></Icon>
<style>
:global(.xiy_pab_o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 4.5l19-2m-9.5 1V8H5v7.5h8.5v-2m3 2V21m3.25-5.5V21");
}

</style>
