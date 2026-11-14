<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzsjkwbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magnetic-shield" {...props}></Icon>
<style>
:global(.pzsjkwbqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l5 1.75V11c0 4.5-2 8-5 10c-3-2-5-5.5-5-10V4.75ZM2.5 7q3.5 5 0 10m19-10q-3.5 5 0 10");
}

</style>
