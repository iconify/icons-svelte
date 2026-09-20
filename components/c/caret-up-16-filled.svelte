<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u9_2bh1qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-up-16-filled" {...props}></Icon>
<style>
:global(.u9_2bh1qp) {
  fill: currentColor;
  d: path("M4.957 10.998a1 1 0 0 1-.821-1.571l2.633-3.784a1.5 1.5 0 0 1 2.462 0l2.633 3.784a1 1 0 0 1-.821 1.571z");
}

</style>
