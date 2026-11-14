<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsyu5clpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:allen-key" {...props}></Icon>
<style>
:global(.tsyu5clpn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21V7a4 4 0 0 1 4-4h8v3h-7.5A1.5 1.5 0 0 0 9 7.5V21Zm0-3h3");
}

</style>
