<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-z2n3bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:navigation-alt-fill-sharp" {...props}></Icon>
<style>
:global(.p-z2n3bcy) {
  fill: currentColor;
  d: path("M18.949 20.684a.999.999 0 0 1-1.396 1.21L12 19.118l-5.553 2.776a.999.999 0 0 1-1.396-1.21l6-18a1 1 0 0 1 1.898 0Z");
}

</style>
