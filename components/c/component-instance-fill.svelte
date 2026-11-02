<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roahvb2is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-instance-fill" {...props}></Icon>
<style>
:global(.roahvb2is) {
  fill: currentColor;
  d: path("M21.707 10.293a2.414 2.414 0 0 1 0 3.414l-8 8a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0Z");
}

</style>
