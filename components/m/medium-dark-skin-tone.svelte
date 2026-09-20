<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="umfav0b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:medium-dark-skin-tone" {...props}></Icon>
<style>
:global(.umfav0b6r) {
  fill: var(--svg-color--af7e57, #AF7E57);
  d: path("M33 30a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3v24z");
}

</style>
