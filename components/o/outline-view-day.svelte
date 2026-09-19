<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktj6559nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-view-day" {...props}></Icon>
<style>
:global(.ktj6559nw) {
  fill: currentColor;
  d: path("M21 18H2v2h19zm-2-8v4H4v-4zm1-2H3c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h17c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1m1-4H2v2h19z");
}

</style>
