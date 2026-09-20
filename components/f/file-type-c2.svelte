<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vzhsnld0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-c2" {...props}></Icon>
<style>
:global(.vzhsnld0w) {
  fill: var(--svg-color--005f91, #005f91);
  d: path("M23 19.418a6.971 6.971 0 1 1-.05-6.918l6.093-3.509a14 14 0 1 0 .036 13.95Z");
}

</style>
