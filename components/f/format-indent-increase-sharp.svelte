<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wty2babvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-indent-increase-sharp" {...props}></Icon>
<style>
:global(.wty2babvj) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm8-4v-2h10v2zm0-4v-2h10v2zm0-4V7h10v2zM3 5V3h18v2zm0 11V8l4 4z");
}

</style>
