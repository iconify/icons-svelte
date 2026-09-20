<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4xovguxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:ad-sharp" {...props}></Icon>
<style>
:global(.x4xovguxz) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V8.154H5z");
}

</style>
