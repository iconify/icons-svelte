<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8ze-btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-warm-up-sharp" {...props}></Icon>
<style>
:global(.mp8ze-btv) {
  fill: currentColor;
  d: path("M11 5.825L6.4 10.4L5 9l7-7l7 7l-1.4 1.425l-4.6-4.6V13h-2zM11 18v-3h2v3zm0 4v-2h2v2z");
}

</style>
