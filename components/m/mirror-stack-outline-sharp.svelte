<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_vgzxvyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mirror-stack-outline-sharp" {...props}></Icon>
<style>
:global(.d_vgzxvyz) {
  fill: currentColor;
  d: path("M14 18v-2h4V4h-6v2.25h-2V2h10v16zm-8 2h6V8H6zm-2 2V6h10v16zm2-2V8zM18 4v12z");
}

</style>
