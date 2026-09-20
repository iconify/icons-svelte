<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mekzwxbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:greater-than-bold" {...props}></Icon>
<style>
:global(.mekzwxbnt) {
  fill: currentColor;
  d: path("M228 128a12 12 0 0 1-6.86 10.84l-152 72a12 12 0 0 1-10.27-21.69L188 128L58.87 66.85a12 12 0 0 1 10.27-21.69l152 72A12 12 0 0 1 228 128");
}

</style>
