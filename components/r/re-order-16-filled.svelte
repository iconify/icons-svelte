<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z1pohglyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-16-filled" {...props}></Icon>
<style>
:global(.z1pohglyh) {
  fill: currentColor;
  d: path("M2.75 9.25h10.5a.75.75 0 0 1 .102 1.493l-.102.007H2.75a.75.75 0 0 1-.102-1.493zh10.5zm0-4h10.5a.75.75 0 0 1 .102 1.493l-.102.007H2.75a.75.75 0 0 1-.102-1.493zh10.5z");
}

</style>
