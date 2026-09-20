<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rklg7vb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-portrait-sharp" {...props}></Icon>
<style>
:global(.rklg7vb0c) {
  fill: currentColor;
  d: path("M4 22V2h16v20z");
}

</style>
