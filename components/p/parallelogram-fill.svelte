<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4naw7quq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:parallelogram-fill" {...props}></Icon>
<style>
:global(.h4naw7quq) {
  fill: currentColor;
  d: path("M17.976 21.217A1 1 0 0 1 17 22H3a1.002 1.002 0 0 1-.976-1.217l4-18A1 1 0 0 1 7 2h14a1.002 1.002 0 0 1 .976 1.217Z");
}

</style>
