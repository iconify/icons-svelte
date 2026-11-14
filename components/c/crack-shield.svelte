<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvs-0zpyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crack-shield" {...props}></Icon>
<style>
:global(.zvs-0zpyj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.25L4.5 5.5v6c0 4.7 2.9 8 6.25 9.5l-1.5-5l2-4L9.5 8Zm3 0L19.5 5.5v6c0 4.7-2.9 8-5.75 9.5l-1.5-5l2-4l-1.75-4Z");
}

</style>
