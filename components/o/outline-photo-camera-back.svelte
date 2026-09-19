<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu2wp5a9w"/><path class="q-7wtupaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-photo-camera-back" {...props}></Icon>
<style>
:global(.hu2wp5a9w) {
  fill: currentColor;
  d: path("M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 14H4V7h4.05l1.83-2h4.24l1.83 2H20z");
}

:global(.q-7wtupaw) {
  fill: currentColor;
  d: path("M11.25 16L9 13l-3 4h12l-3.75-5z");
}

</style>
