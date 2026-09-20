<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tlyt2x6ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-rtl-32-regular" {...props}></Icon>
<style>
:global(.tlyt2x6ww) {
  fill: currentColor;
  d: path("M29 5a1 1 0 0 1 1 1v20a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1M9.793 7.793a1 1 0 0 1 1.414 1.414L5.414 15H24a1 1 0 0 1 0 2H5.414l5.793 5.793a1 1 0 0 1-1.414 1.414l-7.5-7.5a1 1 0 0 1 0-1.414z");
}

</style>
