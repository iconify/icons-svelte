<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbuv6xlgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-align-left-outline-sharp" {...props}></Icon>
<style>
:global(.fbuv6xlgs) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h12v2zm0-4v-2h18v2zm0-4V7h12v2zm0-4V3h18v2z");
}

</style>
