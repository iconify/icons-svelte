<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vfh3i6wms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:couch-bold" {...props}></Icon>
<style>
:global(.vfh3i6wms) {
  fill: currentColor;
  d: path("M244 104V72a20 20 0 0 0-20-20H32a20 20 0 0 0-20 20v32a20 20 0 0 0-8 16v48a20 20 0 0 0 20 20h4v12a12 12 0 0 0 24 0v-12h152v12a12 12 0 0 0 24 0v-12h4a20 20 0 0 0 20-20v-48a20 20 0 0 0-8-16m-24-4h-12a20 20 0 0 0-20 20v4h-48V76h80ZM116 76v48H68v-4a20 20 0 0 0-20-20H36V76Zm112 88H28v-40h16v12a12 12 0 0 0 12 12h144a12 12 0 0 0 12-12v-12h16Z");
}

</style>
