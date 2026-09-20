<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lfehxwgnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:equal-off-12-regular" {...props}></Icon>
<style>
:global(.lfehxwgnq) {
  fill: currentColor;
  d: path("M1.854 1.146a.5.5 0 1 0-.708.708L3.293 4H2a.5.5 0 0 0 0 1h2.293l2 2H2a.5.5 0 0 0 0 1h5.293l2.853 2.854a.5.5 0 0 0 .708-.708zM9.12 7l.988.988A.5.5 0 0 0 10 7zm-3-3l1 1H10a.5.5 0 0 0 0-1z");
}

</style>
