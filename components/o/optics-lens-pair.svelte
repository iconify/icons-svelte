<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv2q0gx6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:optics-lens-pair" {...props}></Icon>
<style>
:global(.tv2q0gx6p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12a2 7 0 1 0 4 0a2 7 0 1 0-4 0Zm8 0a2 7 0 1 0 4 0a2 7 0 1 0-4 0ZM2.5 12h19");
}

</style>
