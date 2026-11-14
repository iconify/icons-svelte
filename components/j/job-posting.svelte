<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8n5t_ixk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:job-posting" {...props}></Icon>
<style>
:global(.d8n5t_ixk) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 2.75h13.75q3.375 0 3.375 3.375v11.75q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375V6.125q0-3.375 3.375-3.375m4.701 4.5H8.5q-2.25 0-2.25 2.25v6q0 2.25 2.25 2.25h7q2.25 0 2.25-2.25v-6q0-2.25-2.25-2.25h-1.326q.076.337.076.75q0 2.25-2.25 2.25T9.75 8q0-.413.076-.75");
}

</style>
