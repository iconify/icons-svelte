<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9yzu4ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-left-fill-sharp" {...props}></Icon>
<style>
:global(.ry9yzu4ev) {
  fill: currentColor;
  d: path("m9.414 8l8.293 8.293a.999.999 0 1 1-1.414 1.414L8 9.414V14a1 1 0 0 1-2 0V7a1 1 0 0 1 1-1h7a1 1 0 0 1 0 2Z");
}

</style>
