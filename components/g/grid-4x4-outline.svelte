<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hamluwbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:grid-4x4-outline" {...props}></Icon>
<style>
:global(.hamluwbgi) {
  fill: currentColor;
  d: path("M6.5 20.5v-3h-3v-1h3v-4h-3v-1h3v-4h-3v-1h3v-3h1v3h4v-3h1v3h4v-3h1v3h3v1h-3v4h3v1h-3v4h3v1h-3v3h-1v-3h-4v3h-1v-3h-4v3zm1-4h4v-4h-4zm5 0h4v-4h-4zm-5-5h4v-4h-4zm5 0h4v-4h-4z");
}

</style>
