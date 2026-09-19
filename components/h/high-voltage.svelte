<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c526wmb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:high-voltage" {...props}></Icon>
<style>
:global(.c526wmb6z) {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m44.5 2l-9 2.5L29.4 2l-9.9 34.4h10.4L20.8 62l22.4-34.4H29.7z");
}

</style>
