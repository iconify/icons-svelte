<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obtsf3bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:maintenance-done" {...props}></Icon>
<style>
:global(.obtsf3bxy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 12.25L7 18.5A1.75 1.75 0 0 1 4.5 16l6.25-6.25a4.75 4.75 0 0 1 6.5-6L14 7l2 2l3.25-3.25a4.75 4.75 0 0 1-6 6.5Zm1.5 5.75l2 2L21 15.75");
}

</style>
