<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rq1jzwcal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cellular-data-2-20-filled" {...props}></Icon>
<style>
:global(.rq1jzwcal) {
  fill: currentColor;
  d: path("M4.75 12a.75.75 0 0 1 .741.639l.009.11v2.496a.75.75 0 0 1-1.492.11L4 15.246V12.75a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .741.639l.009.11v4.496a.75.75 0 0 1-1.492.11L7 15.246V10.75a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .741.639l.008.11v6.501a.75.75 0 0 1-1.49.111l-.009-.11V8.75a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .741.639l.008.11v8.501a.75.75 0 0 1-1.49.111l-.009-.11V6.75a.75.75 0 0 1 .75-.75");
}

</style>
