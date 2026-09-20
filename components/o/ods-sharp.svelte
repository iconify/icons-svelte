<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5r2yac5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ods-sharp" {...props}></Icon>
<style>
:global(.r5r2yac5c) {
  fill: currentColor;
  d: path("M5 15h4V9H5zm1.5-1.5v-3h1v3zM10 15h3.25l.75-.75v-4.5L13.25 9H10zm1.5-1.5v-3h1v3zM15 15h4v-3.65h-2.5v-.85H19V9h-4v3.6h2.5v.9H15zM2 20V4h20v16z");
}

</style>
