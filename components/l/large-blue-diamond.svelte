<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="b8act2bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:large-blue-diamond" {...props}></Icon>
<style>
:global(.b8act2bim) {
  fill: var(--svg-color--0071b8, #0071b8);
  d: path("M2.018 32L32 2.019l29.981 29.98L32 61.982z");
}

</style>
