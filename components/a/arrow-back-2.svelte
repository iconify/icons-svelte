<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my5a9-bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-back-2" {...props}></Icon>
<style>
:global(.my5a9-bfk) {
  fill: currentColor;
  d: path("M16 19L5 12l11-7z");
}

</style>
