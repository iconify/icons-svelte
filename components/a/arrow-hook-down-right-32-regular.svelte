<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ivs-vzbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-hook-down-right-32-regular" {...props}></Icon>
<style>
:global(.ivs-vzbto) {
  fill: currentColor;
  d: path("M22 7a1 1 0 1 1 0 2h-9l-.257.007A5 5 0 0 0 13 19h9.586l-3.293-3.293a1 1 0 1 1 1.414-1.414l5 5a1 1 0 0 1 0 1.414l-5 5l-.076.068a1 1 0 0 1-1.406-1.406l.068-.076L22.586 21H13a7 7 0 0 1-.36-13.991L13 7z");
}

</style>
