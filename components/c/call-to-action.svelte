<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_eto8nlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:call-to-action" {...props}></Icon>
<style>
:global(.t_eto8nlb) {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H3v-3h18z");
}

</style>
