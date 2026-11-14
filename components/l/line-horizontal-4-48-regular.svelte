<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z1c_i1nlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-4-48-regular" {...props}></Icon>
<style>
:global(.z1c_i1nlq) {
  fill: currentColor;
  d: path("M42.75 38a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5zm0-10a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5zm0-10a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5zm0-10a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
