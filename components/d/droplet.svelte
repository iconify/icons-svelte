<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ujzbi0bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:droplet" {...props}></Icon>
<style>
:global(.ujzbi0bos) {
  fill: currentColor;
  d: path("M31.993 2C20.563 17.624 14 32.007 14 43.827C14 53.859 22.064 62 32.001 62C41.946 62 50 53.859 50 43.827C50 32.007 43.245 17.383 31.993 2");
}

</style>
