<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m8pnaeb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:numpad-bold" {...props}></Icon>
<style>
:global(.m8pnaeb1p) {
  fill: currentColor;
  d: path("M84 48a20 20 0 1 1-20-20a20 20 0 0 1 20 20m44-20a20 20 0 1 0 20 20a20 20 0 0 0-20-20m64 40a20 20 0 1 0-20-20a20 20 0 0 0 20 20M64 84a20 20 0 1 0 20 20a20 20 0 0 0-20-20m64 0a20 20 0 1 0 20 20a20 20 0 0 0-20-20m64 0a20 20 0 1 0 20 20a20 20 0 0 0-20-20M64 140a20 20 0 1 0 20 20a20 20 0 0 0-20-20m64 0a20 20 0 1 0 20 20a20 20 0 0 0-20-20m0 56a20 20 0 1 0 20 20a20 20 0 0 0-20-20m64-56a20 20 0 1 0 20 20a20 20 0 0 0-20-20");
}

</style>
