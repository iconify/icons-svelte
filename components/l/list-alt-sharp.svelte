<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4_0x_urt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:list-alt-sharp" {...props}></Icon>
<style>
:global(.d4_0x_urt) {
  fill: currentColor;
  d: path("M7 17h2v-2H7zm0-4h2v-2H7zm0-4h2V7H7zm4 8h6v-2h-6zm0-4h6v-2h-6zm0-4h6V7h-6zM3 21V3h18v18z");
}

</style>
