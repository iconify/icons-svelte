<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ywjdr2bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:medium-light-skin-tone" {...props}></Icon>
<style>
:global(.ywjdr2bqg) {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M10 10h108v108H10z");
}

</style>
