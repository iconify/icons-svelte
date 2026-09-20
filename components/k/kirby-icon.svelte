<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":299};
const content = `<path class="o3s_-obut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:kirby-icon" {...props}></Icon>
<style>
:global(.o3s_-obut) {
  d: path("m128 0l128 74.652v149.362l-128 74.653L0 224.014V74.652zm0 16.782L14.222 83.15v132.366L128 281.877l113.778-66.36V83.15zm56.889 96.996v35.555l-35.556 18.418v2.916h35.556v28.444H71.11v-28.444h35.556v-3.108L71.11 149.333v-35.555L128 144.334z");
}

</style>
