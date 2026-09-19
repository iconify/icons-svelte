<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-x07cbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-desktop-windows" {...props}></Icon>
<style>
:global(.m-x07cbgv) {
  fill: currentColor;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h6v2H8v2h8v-2h-2v-2h6c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

</style>
