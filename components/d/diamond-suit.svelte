<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g7_vbg8je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:diamond-suit" {...props}></Icon>
<style>
:global(.g7_vbg8je) {
  fill: var(--svg-color--e03a4d, #e03a4d);
  d: path("M56.28 32L32.14 63L8 32L32.14 1");
}

</style>
