<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vcmo4fbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-line-down-light" {...props}></Icon>
<style>
:global(.vcmo4fbve) {
  fill: currentColor;
  d: path("M51.76 116.24a6 6 0 0 1 8.48-8.48L122 169.51V32a6 6 0 0 1 12 0v137.51l61.76-61.75a6 6 0 0 1 8.48 8.48l-72 72a6 6 0 0 1-8.48 0ZM216 210H40a6 6 0 0 0 0 12h176a6 6 0 0 0 0-12");
}

</style>
