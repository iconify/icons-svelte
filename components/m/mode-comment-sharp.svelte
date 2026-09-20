<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an3a52lgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mode-comment-sharp" {...props}></Icon>
<style>
:global(.an3a52lgo) {
  fill: currentColor;
  d: path("M3 17V3h18v17.077L17.923 17z");
}

</style>
