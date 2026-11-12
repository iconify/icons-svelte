<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g23q2ac4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-push-fill-round" {...props}></Icon>
<style>
:global(.g23q2ac4g) {
  fill: currentColor;
  d: path("m8.293 5.293l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 5.414v9.757a3 3 0 1 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414");
}

</style>
