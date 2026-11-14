<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_lk_xbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-play" {...props}></Icon>
<style>
:global(.o_lk_xbyp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3L2.5 7L6 11m8-8l3.5 4l-3.414 3.902M11 3l-2 8m5 3l7.5 4l-7.5 4Z");
}

</style>
