<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pia9o7b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:docs-sharp" {...props}></Icon>
<style>
:global(.pia9o7b6o) {
  fill: currentColor;
  d: path("M12 3v6.173h6V21H6V3zm1 0h.654L18 7.462v.711h-5zM9.654 18.173H12.5v-1H9.654zm0-3.788h4.673v-1H9.654z");
}

</style>
