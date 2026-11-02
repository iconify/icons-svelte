<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j724uj-qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-2-fill-round" {...props}></Icon>
<style>
:global(.j724uj-qy) {
  fill: currentColor;
  d: path("M4 5v6h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m18 7v1c0 .265-.105.52-.293.707L17.414 18H21a1 1 0 0 1 0 2h-6a1.002 1.002 0 0 1-.707-1.707L20 12.586V12a2 2 0 0 0-4 0a1 1 0 0 1-2 0a4 4 0 0 1 8 0");
}

</style>
