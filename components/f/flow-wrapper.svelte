<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzbos6ygq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flow-wrapper" {...props}></Icon>
<style>
:global(.wzbos6ygq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a5.5 4.5 0 1 0 11 0a5.5 4.5 0 1 0-11 0Zm0 0l-4-4.5l1.25 2.25L2.5 12l1.25 2.25L2.5 16.5Zm11 0l4-4.5l-1.25 2.25L21.5 12l-1.25 2.25l1.25 2.25Z");
}

</style>
