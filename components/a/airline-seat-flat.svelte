<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxroq1b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:airline-seat-flat" {...props}></Icon>
<style>
:global(.dxroq1b4a) {
  fill: currentColor;
  d: path("M22 11v2H9V7h9c2.21 0 4 1.79 4 4M2 14v2h6v2h8v-2h6v-2zm5.14-1.9a3 3 0 0 0-.04-4.24a3 3 0 0 0-4.24.04a3 3 0 0 0 .04 4.24a3 3 0 0 0 4.24-.04");
}

</style>
