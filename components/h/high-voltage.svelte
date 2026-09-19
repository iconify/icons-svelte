<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h748ltbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:high-voltage" {...props}></Icon>
<style>
:global(.h748ltbds) {
  fill: var(--svg-color--fbb11c, #fbb11c);
  d: path("M32 29L42 1L12 35h20L22 63l30-34");
}

</style>
