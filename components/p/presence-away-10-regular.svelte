<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="abwf_yb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-away-10-regular" {...props}></Icon>
<style>
:global(.abwf_yb0e) {
  fill: currentColor;
  d: path("M5 4.793V3.004a.5.5 0 0 0-1 0V5a.5.5 0 0 0 .146.354l1.5 1.5a.5.5 0 1 0 .708-.707zM10 5A5 5 0 1 1 0 5a5 5 0 0 1 10 0M9 5a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

</style>
