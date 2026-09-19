<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfu6ngbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-store-mall-directory" {...props}></Icon>
<style>
:global(.tfu6ngbld) {
  fill: currentColor;
  d: path("m18.36 9l.6 3H5.04l.6-3zM20 4H4v2h16zm0 3H4l-1 5v2h1v6h10v-6h4v6h2v-6h1v-2zM6 18v-4h6v4z");
}

</style>
