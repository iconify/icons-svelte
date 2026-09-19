<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp75p67iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-send" {...props}></Icon>
<style>
:global(.bp75p67iw) {
  fill: currentColor;
  d: path("M2.01 21L23 12L2.01 3L2 10l15 2l-15 2z");
}

</style>
