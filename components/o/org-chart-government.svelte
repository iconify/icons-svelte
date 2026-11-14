<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci7ptt33j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:org-chart-government" {...props}></Icon>
<style>
:global(.ci7ptt33j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h6v5H9ZM3 15h6v5H3Zm12 0h6v5h-6Zm-3-7v3.5M6 15v-3.5h12V15");
}

</style>
