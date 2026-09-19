<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ygcy4ztxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:large-orange-diamond" {...props}></Icon>
<style>
:global(.ygcy4ztxv) {
  fill: var(--svg-color--f27a52, #f27a52);
  d: path("M2.018 32L32 2.019l29.981 29.98L32 61.982z");
}

</style>
