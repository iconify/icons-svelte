<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2bpz1b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:auto-awesome-motion-outline-sharp" {...props}></Icon>
<style>
:global(.k2bpz1b0k) {
  fill: currentColor;
  d: path("M10 22V10h12v12zm2-2h8v-8h-8zm-6-2V6h12v2H8v10zm-4-4V2h12v2H4v10zm10 6v-8z");
}

</style>
