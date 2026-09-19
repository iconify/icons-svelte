<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyka2jb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-subscriptions" {...props}></Icon>
<style>
:global(.tyka2jb9e) {
  fill: currentColor;
  d: path("M20 8H4V6h16zm-2-6H6v2h12zm4 10v8c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2v-8c0-1.1.9-2 2-2h16c1.1 0 2 .9 2 2m-6 4l-6-3.27v6.53z");
}

</style>
