<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shluewb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:developer-guide-sharp" {...props}></Icon>
<style>
:global(.shluewb7s) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm8.5-15v6.116l2-1.193l2 1.193V5z");
}

</style>
