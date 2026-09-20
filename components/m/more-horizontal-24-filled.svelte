<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8kkut_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-24-filled" {...props}></Icon>
<style>
:global(.kl8kkut_d) {
  fill: currentColor;
  d: path("M8 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0m6 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0m4 2a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
