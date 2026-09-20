<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ug9-2zbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:medium-skin-tone" {...props}></Icon>
<style>
:global(.ug9-2zbjl) {
  fill: var(--svg-color--bf8f68, #bf8f68);
  d: path("M10 10h108v108H10z");
}

</style>
