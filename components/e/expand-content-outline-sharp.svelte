<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7q4fxgdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:expand-content-outline-sharp" {...props}></Icon>
<style>
:global(.e7q4fxgdu) {
  fill: currentColor;
  d: path("M6 18v-5h1v4h4v1zm11-7V7h-4V6h5v5z");
}

</style>
