<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q6uxv9oro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:blue-circle" {...props}></Icon>
<style>
:global(.q6uxv9oro) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2");
}

</style>
