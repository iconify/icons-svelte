<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atr7d-maa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dropdown-sharp" {...props}></Icon>
<style>
:global(.atr7d-maa) {
  fill: currentColor;
  d: path("M11 13h7V6h-7zm-8 8V3h18v18z");
}

</style>
