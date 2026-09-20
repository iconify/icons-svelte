<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sgs5swrgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-two-split-top-20-filled" {...props}></Icon>
<style>
:global(.sgs5swrgw) {
  fill: currentColor;
  d: path("M9.5 9.5V3H6a3 3 0 0 0-3 3v3.5zm1 0H17V6a3 3 0 0 0-3-3h-3.5zm6.5 1H3V14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3z");
}

</style>
