<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewwdgpbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrows-more-down-outline-sharp" {...props}></Icon>
<style>
:global(.ewwdgpbmu) {
  fill: currentColor;
  d: path("M5 21V10h2v9h9v2zm5-5V5h2v9h9v2z");
}

</style>
