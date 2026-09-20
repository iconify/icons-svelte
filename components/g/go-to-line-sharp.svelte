<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr62x5iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:go-to-line-sharp" {...props}></Icon>
<style>
:global(.zr62x5iew) {
  fill: currentColor;
  d: path("M10.5 7V4h3v3zm0 13v-3h3v3z");
}

</style>
