<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ky_fbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-home" {...props}></Icon>
<style>
:global(.i2ky_fbxv) {
  fill: currentColor;
  d: path("M10 20v-6h4v6h5v-8h3L12 3L2 12h3v8z");
}

</style>
