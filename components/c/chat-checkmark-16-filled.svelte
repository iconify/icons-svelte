<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nhkia3q3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chat-checkmark-16-filled" {...props}></Icon>
<style>
:global(.nhkia3q3m) {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m2.854 5.147a.5.5 0 0 0-.707 0L7.25 9.043L5.854 7.647a.5.5 0 0 0-.708.707l1.75 1.75a.5.5 0 0 0 .708 0l3.25-3.25a.5.5 0 0 0 0-.708");
}

</style>
