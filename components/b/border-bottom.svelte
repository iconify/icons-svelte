<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n765p86ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-bottom" {...props}></Icon>
<style>
:global(.n765p86ft) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 8v-2h2v2zm0-8V3h2v2zm4 12v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 8v-2h2v2zm0-8V3h2v2zm4 12v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2z");
}

</style>
