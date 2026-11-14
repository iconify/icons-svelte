<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9fudbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-4-24-filled" {...props}></Icon>
<style>
:global(.lh9fudbbd) {
  fill: currentColor;
  d: path("M21 18a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 0 1 0-2z");
}

</style>
