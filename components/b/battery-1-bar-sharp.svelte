<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oezn665qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-1-bar-sharp" {...props}></Icon>
<style>
:global(.oezn665qv) {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18zm2-4h6V6H9z");
}

</style>
