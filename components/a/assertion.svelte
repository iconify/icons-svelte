<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvv4nfck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:assertion" {...props}></Icon>
<style>
:global(.nnvv4nfck) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 10.5l5 5l10-10M4 20.5h16");
}

</style>
