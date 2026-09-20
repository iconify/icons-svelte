<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdp6gwbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-mobile-sharp" {...props}></Icon>
<style>
:global(.vdp6gwbtk) {
  fill: currentColor;
  d: path("M20 22H4V2h16zm-3-9V5h-6v8z");
}

</style>
