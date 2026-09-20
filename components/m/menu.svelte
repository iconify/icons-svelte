<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zo5346bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:menu" {...props}></Icon>
<style>
:global(.zo5346bid) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 8a1 1 0 0 1 1-1h10.308a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m0-4a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m0 8a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m0 4a1 1 0 0 1 1-1h10.308a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1");
}

</style>
