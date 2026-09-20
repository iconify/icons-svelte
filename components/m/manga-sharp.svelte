<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgbcscary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:manga-sharp" {...props}></Icon>
<style>
:global(.qgbcscary) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6.1-2H20V7.025L17 8l-3.075-1L12 9.625l-3.075 1v3.25l-1.9 2.625z");
}

</style>
