<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mblvlqjes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:list-24-regular" {...props}></Icon>
<style>
:global(.mblvlqjes) {
  fill: currentColor;
  d: path("M2 5.75A.75.75 0 0 1 2.75 5h15.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 5.75m0 12a.75.75 0 0 1 .75-.75h12.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75M2.75 11a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
