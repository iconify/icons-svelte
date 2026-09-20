<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0jcrbcgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-shape-up" {...props}></Icon>
<style>
:global(.u0jcrbcgr) {
  fill: currentColor;
  d: path("M8 21v-6H3l9-11l9 11h-5v6z");
}

</style>
