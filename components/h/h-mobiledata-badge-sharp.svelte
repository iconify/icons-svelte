<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf7ntv5yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:h-mobiledata-badge-sharp" {...props}></Icon>
<style>
:global(.cf7ntv5yx) {
  fill: currentColor;
  d: path("M8.692 16.5h1v-4h4.616v4h1v-9h-1v4H9.692v-4h-1zM4 20V4h16v16z");
}

</style>
