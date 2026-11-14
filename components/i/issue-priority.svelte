<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quyy_r0lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:issue-priority" {...props}></Icon>
<style>
:global(.quyy_r0lc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm7-4.5v6m0 3h.01m3.99-9v6m0 3h.01");
}

</style>
