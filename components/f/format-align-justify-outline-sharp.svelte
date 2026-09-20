<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu5_s-p_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-align-justify-outline-sharp" {...props}></Icon>
<style>
:global(.nu5_s-p_d) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h18v2zm0-4v-2h18v2zm0-4V7h18v2zm0-4V3h18v2z");
}

</style>
