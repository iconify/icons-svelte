<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkhgqchzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-24-regular" {...props}></Icon>
<style>
:global(.kkhgqchzu) {
  fill: currentColor;
  d: path("M2.75 13.25h18.5a.75.75 0 0 1 .102 1.493l-.102.007H2.75a.75.75 0 0 1-.102-1.493zh18.5zm0-4h18.5a.75.75 0 0 1 .102 1.493l-.102.007H2.75a.75.75 0 0 1-.102-1.493zh18.5z");
}

</style>
