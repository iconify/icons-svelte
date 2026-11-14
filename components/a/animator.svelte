<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsu1ifbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:animator" {...props}></Icon>
<style>
:global(.hsu1ifbji) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h6l1.5 4l-4.5 5.5L7.5 7Zm3 4.5v5m-9 6q4.5-5.25 9 0t9 0");
}

</style>
