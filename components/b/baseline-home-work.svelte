<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnhu26bxu"/><path class="t4vrjsbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-home-work" {...props}></Icon>
<style>
:global(.t4vrjsbgu) {
  fill: currentColor;
  d: path("M10 3v1.97l7 5V11h2v2h-2v2h2v2h-2v4h6V3zm9 6h-2V7h2z");
}

:global(.tnhu26bxu) {
  fill: currentColor;
  d: path("M1 11v10h5v-6h4v6h5V11L8 6z");
}

</style>
