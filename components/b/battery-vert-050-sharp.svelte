<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzxd0nn_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-vert-050-sharp" {...props}></Icon>
<style>
:global(.qzxd0nn_c) {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18H7Zm2-9h6V6H9v7Z");
}

</style>
