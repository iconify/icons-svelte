<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nata3ac8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:medium-dark-skin-tone" {...props}></Icon>
<style>
:global(.nata3ac8n) {
  fill: var(--svg-color--9b643c, #9b643c);
  d: path("M10 10h108v108H10z");
}

</style>
