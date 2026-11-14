<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu9bw6ehn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cargo-net" {...props}></Icon>
<style>
:global(.wu9bw6ehn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m6 0l8 6.5l-8 6.5l-8-6.5ZM3 20h18");
}

</style>
