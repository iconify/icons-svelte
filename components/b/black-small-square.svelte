<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tjktpnt8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:black-small-square" {...props}></Icon>
<style>
:global(.tjktpnt8t) {
  fill: var(--svg-color--212121, #212121);
  d: path("M50.04 50.04h27.91v27.92H50.04z");
}

</style>
