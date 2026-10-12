<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqlvppbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ratio-21-9-sharp-fill" {...props}></Icon>
<style>
:global(.kqlvppbvy) {
  fill: currentColor;
  d: path("M2 7L22 7C22.5523 7 23 7.4477 23 8L23 16C23 16.5523 22.5523 17 22 17L2 17C1.4477 17 1 16.5523 1 16L1 8C1 7.4477 1.4477 7 2 7Z");
}

</style>
