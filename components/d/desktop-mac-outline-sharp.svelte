<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a6rpb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:desktop-mac-outline-sharp" {...props}></Icon>
<style>
:global(.n0a6rpb_d) {
  fill: currentColor;
  d: path("M8 21v-1l2-2H2V3h20v15h-8l2 2v1zm-4-8h16V5H4zm0 0V5z");
}

</style>
