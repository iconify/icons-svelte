<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp-rwpbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:first-page" {...props}></Icon>
<style>
:global(.rp-rwpbej) {
  fill: currentColor;
  d: path("M6 18V6h2v12zm11 0l-6-6l6-6l1.4 1.4l-4.6 4.6l4.6 4.6z");
}

</style>
