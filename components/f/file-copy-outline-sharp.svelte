<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_hffbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:file-copy-outline-sharp" {...props}></Icon>
<style>
:global(.tx_hffbgl) {
  fill: currentColor;
  d: path("M6 19V1h9l6 6v12zm8-11V3H8v14h11V8zM2 23V7h2v14h11v2zM8 3v5zv14z");
}

</style>
