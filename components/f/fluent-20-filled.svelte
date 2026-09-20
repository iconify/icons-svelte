<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ppyof5l8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:fluent-20-filled" {...props}></Icon>
<style>
:global(.ppyof5l8c) {
  fill: currentColor;
  d: path("M10.724 2.053a.5.5 0 0 0-.448 0l-5 2.5A.5.5 0 0 0 5 5v9.5a.5.5 0 0 0 .243.429l5 3A.5.5 0 0 0 11 17.5v-4.691l4.724-2.362a.5.5 0 0 0 0-.894L11.618 7.5l4.106-2.053a.5.5 0 0 0 0-.894z");
}

</style>
