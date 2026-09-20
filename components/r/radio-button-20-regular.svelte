<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7zz_f2xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:radio-button-20-regular" {...props}></Icon>
<style>
:global(.g7zz_f2xs) {
  fill: currentColor;
  d: path("M10 3a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-8 7a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

</style>
