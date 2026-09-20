<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw0xznbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:magnification-small-outline-sharp" {...props}></Icon>
<style>
:global(.tw0xznbgc) {
  fill: currentColor;
  d: path("M5 11h4V7H5zm-3 9V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
