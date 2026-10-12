<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do9si3bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:async-sharp" {...props}></Icon>
<style>
:global(.do9si3bfu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25H20M17 4l3.25 3.25L17 10.5M2.75 16.75h2.5m3 0H20m-3-3.25l3.25 3.25L17 20");
}

</style>
