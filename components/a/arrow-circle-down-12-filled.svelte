<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gllufzigv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-circle-down-12-filled" {...props}></Icon>
<style>
:global(.gllufzigv) {
  fill: currentColor;
  d: path("M11 6A5 5 0 1 1 1 6a5 5 0 0 1 10 0m-2.646.098a.5.5 0 0 0-.708 0L6.5 7.244V3.5a.5.5 0 0 0-1 0v3.744L4.354 6.098a.5.5 0 1 0-.708.707l2 2a.5.5 0 0 0 .708 0l2-2a.5.5 0 0 0 0-.707");
}

</style>
