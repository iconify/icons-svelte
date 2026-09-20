<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z2f9o-5ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-treemap-20-filled" {...props}></Icon>
<style>
:global(.z2f9o-5ai) {
  fill: currentColor;
  d: path("M7 3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h1zm1 14h6a3 3 0 0 0 3-3v-1H8zm9-5V6a3 3 0 0 0-3-3H8v9z");
}

</style>
