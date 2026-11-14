<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw-p4rb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:home-mode-selector" {...props}></Icon>
<style>
:global(.vw-p4rb6x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 14.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6 0V11m0-7.25v2m-7.5 4.5l-1.75-1m16.75 1l1.75-1");
}

</style>
