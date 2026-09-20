<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4a22tbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-back-2-sharp" {...props}></Icon>
<style>
:global(.j4a22tbhd) {
  fill: currentColor;
  d: path("M15 17.192L6.846 12L15 6.808z");
}

</style>
