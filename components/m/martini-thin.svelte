<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kpzngqurn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:martini-thin" {...props}></Icon>
<style>
:global(.kpzngqurn) {
  fill: currentColor;
  d: path("M234.83 42.83A4 4 0 0 0 232 36H24a4 4 0 0 0-2.83 6.83L124 145.66V212H88a4 4 0 0 0 0 8h80a4 4 0 0 0 0-8h-36v-66.34ZM33.66 44h188.68l-24 24H57.66ZM128 138.34L65.66 76h124.68Z");
}

</style>
