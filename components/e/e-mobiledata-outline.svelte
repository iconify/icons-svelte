<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbclqw6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:e-mobiledata-outline" {...props}></Icon>
<style>
:global(.vxbclqw6i) {
  fill: currentColor;
  d: path("M8.5 17V7h7v1h-6v3.5h6v1h-6V16h6v1z");
}

</style>
