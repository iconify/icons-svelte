<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0cgwzr6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mushroom-lamp" {...props}></Icon>
<style>
:global(.b0cgwzr6b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11a8.5 8.5 0 0 1 17 0Zm8.5 0v7m-5.5 3a5.5 3 0 0 1 11 0Z");
}

</style>
