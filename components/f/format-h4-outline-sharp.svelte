<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hewpuwg6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-h4-outline-sharp" {...props}></Icon>
<style>
:global(.hewpuwg6v) {
  fill: currentColor;
  d: path("M4 16.5v-9h1v4h5v-4h1v9h-1v-4H5v4zm14 0v-3h-5v-6h1v5h4v-5h1v5h2v1h-2v3z");
}

</style>
