<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvf914b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:closed-sign" {...props}></Icon>
<style>
:global(.vvf914b_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h16M8 3v5m8-5v5M3 8h18v13.5H3Zm5.25 3l7.5 7.5m0-7.5l-7.5 7.5");
}

</style>
