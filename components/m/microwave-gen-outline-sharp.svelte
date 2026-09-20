<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-bffbbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:microwave-gen-outline-sharp" {...props}></Icon>
<style>
:global(.i-bffbbdb) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm1-1h10V7H5zm2-2V9h6v6zm10-6h2V7h-2zm0 4h2v-2h-2zm0 4h2v-2h-2zM4 18V6z");
}

</style>
