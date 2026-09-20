<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6bwznxdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:call-to-action-outline-sharp" {...props}></Icon>
<style>
:global(.d6bwznxdk) {
  fill: currentColor;
  d: path("M6 17h12v-3H6zm-4 3V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
