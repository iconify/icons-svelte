<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k9jca4tfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:black-medium-small-square" {...props}></Icon>
<style>
:global(.k9jca4tfl) {
  fill: var(--svg-color--212121, #212121);
  d: path("M40.03 40.02h47.95v47.95H40.03z");
}

</style>
