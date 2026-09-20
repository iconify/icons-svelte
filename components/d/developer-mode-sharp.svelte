<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzw3lhjtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:developer-mode-sharp" {...props}></Icon>
<style>
:global(.dzw3lhjtj) {
  fill: currentColor;
  d: path("M8.6 16.6L4 12l4.6-4.6L10 8.85L6.85 12L10 15.15zM5 17h2v1h10v-1h2v6H5zM7 7H5V1h14v6h-2V6H7zm8.4 9.6L14 15.15L17.15 12L14 8.85l1.4-1.45L20 12z");
}

</style>
