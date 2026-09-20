<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="gv3hcsb8h"/><path class="jh41v0x-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-vietnam" {...props}></Icon>
<style>
:global(.gv3hcsb8h) {
  fill: var(--svg-color--da251d, #da251d);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.jh41v0x-q) {
  fill: var(--svg-color--ff0, #ff0);
  d: path("M19.753 16.037L18 10.642l-1.753 5.395h-5.672l4.589 3.333l-1.753 5.395L18 21.431l4.589 3.334l-1.753-5.395l4.589-3.333z");
}

</style>
