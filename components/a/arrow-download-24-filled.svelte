<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iie8-obpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-download-24-filled" {...props}></Icon>
<style>
:global(.iie8-obpo) {
  fill: currentColor;
  d: path("M13 3a1 1 0 1 0-2 0v12.086l-3.293-3.293a1 1 0 0 0-1.414 1.414l5 5a1 1 0 0 0 1.414 0l5-5a1 1 0 0 0-1.414-1.414L13 15.086zM5 20a1 1 0 1 0 0 2h14a1 1 0 1 0 0-2z");
}

</style>
