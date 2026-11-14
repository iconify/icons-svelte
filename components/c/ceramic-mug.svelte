<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae12a14ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ceramic-mug" {...props}></Icon>
<style>
:global(.ae12a14ed) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h12v12a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm12 4h1.5a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H16");
}

</style>
