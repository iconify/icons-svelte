<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q600ioy0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:line-vertical-light" {...props}></Icon>
<style>
:global(.q600ioy0k) {
  fill: currentColor;
  d: path("M134 24v208a6 6 0 0 1-12 0V24a6 6 0 0 1 12 0");
}

</style>
