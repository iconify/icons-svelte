<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjfj3lbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bike-mirror" {...props}></Icon>
<style>
:global(.gjfj3lbxp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14q4.5 4.5 11 3.5m2-2h4a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2a2 2 0 0 1 2-2m-9.5 1v5m11-6l-.25-4M12 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
