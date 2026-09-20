<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1trt_b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dynamic-feed-outline-sharp" {...props}></Icon>
<style>
:global(.n1trt_b3v) {
  fill: currentColor;
  d: path("M2 21v-9h2v7h9v2zm4-4V8h2v7h9v2zm4-4V3h12v10zm2-2h8V7h-8z");
}

</style>
