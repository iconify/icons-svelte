<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7l086bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chimney-stack" {...props}></Icon>
<style>
:global(.u7l086bdj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5H10v3H3.5Zm1 3v14H9v-14m5.75 0A1.75 1.75 0 0 1 16 4.25a2.5 2.5 0 0 1 4.5 0a1.75 1.75 0 0 1 0 3.25Z");
}

</style>
