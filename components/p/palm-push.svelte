<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx7213bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:palm-push" {...props}></Icon>
<style>
:global(.yx7213bzi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8v7.5A5.5 5.5 0 0 0 8 21h1a5.5 5.5 0 0 0 5.5-5.5V7m-9-2v7m3-8.5V12m3-7.5V12m6 0h4.25M19.5 9.75L21.75 12l-2.25 2.25");
}

</style>
