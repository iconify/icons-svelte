<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r83z8fr5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fullscreen-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.r83z8fr5o) {
  fill: currentColor;
  d: path("M8 18h8V6H8zm12 4H4V2h16zm-2-2V4H6v16zm0-16H6z");
}

</style>
