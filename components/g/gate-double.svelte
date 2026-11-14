<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exn2zpisn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gate-double" {...props}></Icon>
<style>
:global(.exn2zpisn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v16.5M21 4v16.5M6 6q3 3.5 6 3.5T18 6v12H6Zm6 3.5V18m-6-4h12");
}

</style>
