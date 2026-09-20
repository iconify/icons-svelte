<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdtxac7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-end-sharp" {...props}></Icon>
<style>
:global(.fmdtxac7y) {
  fill: currentColor;
  d: path("M3 21v-1h18v1zm4.5-10.5v-2h9v2zm0 6v-2h9v2z");
}

</style>
