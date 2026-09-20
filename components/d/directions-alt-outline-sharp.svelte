<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z88-qi4kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:directions-alt-outline-sharp" {...props}></Icon>
<style>
:global(.z88-qi4kf) {
  fill: currentColor;
  d: path("M12 22.8L1.2 12L12 1.2L22.8 12zm0-2.8l8-8l-8-8l-8 8zm0-3l5-5l-5-5l-1.4 1.4l2.55 2.6H7v2h6.15l-2.55 2.6zm0-5");
}

</style>
