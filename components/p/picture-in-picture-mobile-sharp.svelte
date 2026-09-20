<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evkeupb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-mobile-sharp" {...props}></Icon>
<style>
:global(.evkeupb5s) {
  fill: currentColor;
  d: path("M19 21H5V3h14zm-2.039-8.308V5H11.27v7.692z");
}

</style>
