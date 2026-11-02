<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwiwjnbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-triangle-fill-sharp" {...props}></Icon>
<style>
:global(.cwiwjnbbn) {
  fill: currentColor;
  d: path("M18.447 8.106a.998.998 0 0 1 0 1.788L7 15.618V21a1 1 0 0 1-2 0V3a1 1 0 0 1 1.447-.894Z");
}

</style>
