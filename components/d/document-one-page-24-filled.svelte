<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cigdmkbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-one-page-24-filled" {...props}></Icon>
<style>
:global(.cigdmkbtk) {
  fill: currentColor;
  d: path("M6.25 2A2.25 2.25 0 0 0 4 4.25v15.5A2.25 2.25 0 0 0 6.25 22h11.5A2.25 2.25 0 0 0 20 19.75V4.25A2.25 2.25 0 0 0 17.75 2zm1.5 4h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5M7 16.75a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75M7.75 11h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5");
}

</style>
