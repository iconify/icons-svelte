<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmyft4pud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:play-arrow-sharp" {...props}></Icon>
<style>
:global(.gmyft4pud) {
  fill: currentColor;
  d: path("M8 19V5l11 7z");
}

</style>
