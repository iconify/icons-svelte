<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qfw6bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eject-fill-sharp" {...props}></Icon>
<style>
:global(.i1qfw6bry) {
  fill: currentColor;
  d: path("m4.136 15.496l7-12a1 1 0 0 1 1.728 0l7 12A1.002 1.002 0 0 1 19 17H5a.998.998 0 0 1-.864-1.504M19 19a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
