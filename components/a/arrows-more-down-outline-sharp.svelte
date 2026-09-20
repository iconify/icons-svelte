<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr1-__bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrows-more-down-outline-sharp" {...props}></Icon>
<style>
:global(.yr1-__bll) {
  fill: currentColor;
  d: path("M6 20V10h1v9h9v1zm4-4V6h1v9h9v1z");
}

</style>
