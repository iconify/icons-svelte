<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c9mt5evfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:black-medium-square" {...props}></Icon>
<style>
:global(.c9mt5evfe) {
  fill: var(--svg-color--212121, #212121);
  d: path("M23 23h82v82H23z");
}

</style>
