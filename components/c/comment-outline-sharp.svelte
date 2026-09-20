<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk28gt36c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:comment-outline-sharp" {...props}></Icon>
<style>
:global(.bk28gt36c) {
  fill: currentColor;
  d: path("M6 14h12v-2H6zm0-3h12V9H6zm0-3h12V6H6zM2 18V2h20v20l-4-4zm2-2h14.85L20 17.125V4H4zm0 0V4z");
}

</style>
