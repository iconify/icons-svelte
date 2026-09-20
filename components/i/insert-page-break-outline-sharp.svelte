<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1cd1bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:insert-page-break-outline-sharp" {...props}></Icon>
<style>
:global(.ei1cd1bgv) {
  fill: currentColor;
  d: path("M4 22v-5h2v3h12v-3h2v5zm0-11V2h10l6 6v3h-2V9h-5V4H6v7zm5 4v-2h6v2zm8 0v-2h6v2zM1 15v-2h6v2zm11 2");
}

</style>
