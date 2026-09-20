<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo3uywbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:call-to-action-outline-sharp" {...props}></Icon>
<style>
:global(.zo3uywbdg) {
  fill: currentColor;
  d: path("M6.5 16.5h11v-2h-11zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
