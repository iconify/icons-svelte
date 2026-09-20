<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x9m_s6bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:plus-light" {...props}></Icon>
<style>
:global(.x9m_s6bmh) {
  fill: currentColor;
  d: path("M222 128a6 6 0 0 1-6 6h-82v82a6 6 0 0 1-12 0v-82H40a6 6 0 0 1 0-12h82V40a6 6 0 0 1 12 0v82h82a6 6 0 0 1 6 6");
}

</style>
