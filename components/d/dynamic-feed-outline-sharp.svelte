<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy-qzsb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dynamic-feed-outline-sharp" {...props}></Icon>
<style>
:global(.sy-qzsb3v) {
  fill: currentColor;
  d: path("M3.23 19.77v-7.231h1v6.23h8.232v1zM7 16V8.77h1V15h8.23v1zm3.77-3.77v-8h10v8zm1-1h8v-4h-8z");
}

</style>
