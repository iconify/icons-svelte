<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esaf4sbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cellular-data-3-24-regular" {...props}></Icon>
<style>
:global(.esaf4sbbk) {
  fill: currentColor;
  d: path("M3.75 17a.75.75 0 0 1 .743.648l.007.102v1.5a.75.75 0 0 1-1.493.102L3 19.25v-1.5a.75.75 0 0 1 .75-.75m8-6a.75.75 0 0 1 .743.648l.007.102v7.5a.75.75 0 0 1-1.493.102L11 19.25v-7.5a.75.75 0 0 1 .75-.75m-4 3a.75.75 0 0 1 .743.648l.007.102v4.499a.75.75 0 0 1-1.493.102L7 19.249V14.75a.75.75 0 0 1 .75-.75");
}

</style>
