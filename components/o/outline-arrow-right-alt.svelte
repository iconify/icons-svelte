<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h47nqikvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-arrow-right-alt" {...props}></Icon>
<style>
:global(.h47nqikvi) {
  fill: currentColor;
  d: path("M16.01 11H4v2h12.01v3L20 12l-3.99-4z");
}

</style>
