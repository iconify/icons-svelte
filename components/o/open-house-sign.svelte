<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2dr5-ose"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:open-house-sign" {...props}></Icon>
<style>
:global(.s2dr5-ose) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5h17M7 20.5L12 5l5 15.5m-8-6h6");
}

</style>
