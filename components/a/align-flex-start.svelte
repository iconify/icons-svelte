<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p38njhtgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-flex-start" {...props}></Icon>
<style>
:global(.p38njhtgy) {
  fill: currentColor;
  d: path("M3 4V3h18v1zm8 16V7h2v13z");
}

</style>
