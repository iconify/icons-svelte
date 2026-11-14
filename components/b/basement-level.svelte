<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4qgl6bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:basement-level" {...props}></Icon>
<style>
:global(.u4qgl6bvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.5v-13L12 3l6 5.5v13ZM6 10h12M2.5 15.5h2m3 0h2m1.5 0h2m1.5 0h2m3 0h2");
}

</style>
