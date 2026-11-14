<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-k53j1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dotara" {...props}></Icon>
<style>
:global(.q1-k53j1c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m4-11l-1-2.5h5l-1 2.5Zm0 0v13.5m3-13.5v13.5m-3.5 0h4");
}

</style>
