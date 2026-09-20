<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dojo7xbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-keys-outline" {...props}></Icon>
<style>
:global(.dojo7xbge) {
  fill: currentColor;
  d: path("M7 17v-2h10v2zm-4-4v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zM3 9V7h2v2zm4 0V7h2v2zm4 0V7h2v2zm4 0V7h2v2zm4 0V7h2v2z");
}

</style>
