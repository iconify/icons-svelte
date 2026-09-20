<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z80ox4b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-lean" {...props}></Icon>
<style>
:global(.z80ox4b3w) {
  fill: none;
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 3l13 25L29 3M10 16h12");
}

</style>
