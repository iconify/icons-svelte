<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="vfhmwrxgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:light-skin-tone" {...props}></Icon>
<style>
:global(.vfhmwrxgq) {
  fill: var(--svg-color--f7dece, #F7DECE);
  d: path("M33 30a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3v24z");
}

</style>
