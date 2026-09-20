<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km2rc11vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:breaking-news-alt-1-sharp" {...props}></Icon>
<style>
:global(.km2rc11vh) {
  fill: currentColor;
  d: path("M6 17h5v-2H6zm10 0h2v-2h-2zM6 13h5v-2H6zm10 0h2V7h-2zM6 9h5V7H6zM2 21V3h20v18z");
}

</style>
