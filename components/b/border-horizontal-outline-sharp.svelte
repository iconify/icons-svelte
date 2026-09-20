<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou67ikz8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:border-horizontal-outline-sharp" {...props}></Icon>
<style>
:global(.ou67ikz8b) {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h18v2zm0-4V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zM7 5V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2z");
}

</style>
