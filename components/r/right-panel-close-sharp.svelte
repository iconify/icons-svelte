<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om7i8tbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:right-panel-close-sharp" {...props}></Icon>
<style>
:global(.om7i8tbvs) {
  fill: currentColor;
  d: path("m7.5 16l4-4l-4-4zM5 19h9V5H5zm-2 2V3h18v18z");
}

</style>
