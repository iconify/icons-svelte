<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1i_uabgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:check-box-outline-blank-sharp" {...props}></Icon>
<style>
:global(.y1i_uabgk) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5z");
}

</style>
