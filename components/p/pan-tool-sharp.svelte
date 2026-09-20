<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax_5wmfhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pan-tool-sharp" {...props}></Icon>
<style>
:global(.ax_5wmfhj) {
  fill: currentColor;
  d: path("M8.475 23L1.2 12.375l1.725-1.65L7 13.575V3h2v9h2V1h2v11h2V2h2v10h2V4h2v19z");
}

</style>
