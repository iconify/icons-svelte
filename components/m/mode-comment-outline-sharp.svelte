<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln-fcwbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mode-comment-outline-sharp" {...props}></Icon>
<style>
:global(.ln-fcwbuf) {
  fill: currentColor;
  d: path("M2 18V2h20v20l-4-4zm2-2h14.85L20 17.125V4H4zm0 0V4z");
}

</style>
