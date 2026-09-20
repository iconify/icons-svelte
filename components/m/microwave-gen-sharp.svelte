<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgkahhb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:microwave-gen-sharp" {...props}></Icon>
<style>
:global(.sgkahhb1a) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h10V7H5zm2-2V9h6v6zm10-6h2V7h-2zm0 4h2v-2h-2zm0 4h2v-2h-2z");
}

</style>
