<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":230};
const content = `<path class="iulkdfb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:aerospike-icon" {...props}></Icon>
<style>
:global(.iulkdfb1v) {
  fill: var(--svg-color--c4373a, #c4373a);
  d: path("M256 0v27.43l-60.039 26.468v123.077L256 203.728v26.18L27.017 126.865L0 115.372l27.017-12.389zm-83.138 63.932l-115.943 51.36l115.943 51.647z");
}

</style>
