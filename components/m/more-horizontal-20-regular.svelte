<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xxmekcxlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-20-regular" {...props}></Icon>
<style>
:global(.xxmekcxlq) {
  fill: currentColor;
  d: path("M6.25 10a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M15 11.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

</style>
