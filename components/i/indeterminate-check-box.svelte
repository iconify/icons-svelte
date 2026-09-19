<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqwh5b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:indeterminate-check-box" {...props}></Icon>
<style>
:global(.yzqwh5b9z) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-2 10H7v-2h10z");
}

</style>
