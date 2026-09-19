<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1e067yag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-horizontal-rule" {...props}></Icon>
<style>
:global(.e1e067yag) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 11h16v2H4z");
}

</style>
