<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkpvchb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-drop-down-outline-sharp" {...props}></Icon>
<style>
:global(.gkpvchb-b) {
  fill: currentColor;
  d: path("m12 15l-5-5h10z");
}

</style>
