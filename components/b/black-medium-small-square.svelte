<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="u287gebsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:black-medium-small-square" {...props}></Icon>
<style>
:global(.u287gebsh) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M29 27a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h18a2 2 0 0 1 2 2z");
}

</style>
