<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z-3stebpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:light-skin-tone" {...props}></Icon>
<style>
:global(.z-3stebpd) {
  fill: var(--svg-color--fadcbc, #fadcbc);
  d: path("M10 10h108v108H10z");
}

</style>
