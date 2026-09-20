<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fenq5cbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:line-slant-up" {...props}></Icon>
<style>
:global(.fenq5cbte) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M.808 19.193a1 1 0 0 1 0-1.415L17.778.808a1 1 0 1 1 1.414 1.414l-16.97 16.97a1 1 0 0 1-1.414 0");
}

</style>
