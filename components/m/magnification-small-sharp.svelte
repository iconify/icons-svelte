<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bxbdctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:magnification-small-sharp" {...props}></Icon>
<style>
:global(.w-bxbdctz) {
  fill: currentColor;
  d: path("M5.5 10.5h3v-3h-3zM3 19V5h18v14z");
}

</style>
