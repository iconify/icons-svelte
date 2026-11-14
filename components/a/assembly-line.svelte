<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7n-zhz1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:assembly-line" {...props}></Icon>
<style>
:global(.y7n-zhz1v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19v5h-19Zm3 2.5h.01m12.99 0h.01M3.5 5.5h6v5.25h-6Zm11 0h6v5.25h-6Z");
}

</style>
