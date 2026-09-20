<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="szdhc8bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:medium-skin-tone" {...props}></Icon>
<style>
:global(.szdhc8bba) {
  fill: var(--svg-color--d5ab88, #D5AB88);
  d: path("M33 30a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3v24z");
}

</style>
