<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jw_yhbbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:default-file" {...props}></Icon>
<style>
:global(.jw_yhbbxl) {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M20.414 2H5v28h22V8.586ZM7 28V4h12v6h6v18Z");
}

</style>
