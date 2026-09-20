<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaevpkbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:package-sharp" {...props}></Icon>
<style>
:global(.gaevpkbbp) {
  fill: currentColor;
  d: path("M7 17h5v-2H7zm-4 4V3h18v18zM8 5v8l4-2l4 2V5z");
}

</style>
