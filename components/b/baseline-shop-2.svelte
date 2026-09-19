<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcg6jsbkc"/><path class="m2lf9ebbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-shop-2" {...props}></Icon>
<style>
:global(.m2lf9ebbd) {
  fill: currentColor;
  d: path("M18 5V3c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H5v11c0 1.11.89 2 2 2h14c1.11 0 2-.89 2-2V5zm-6-2h4v2h-4zm0 12V8l5.5 3.5z");
}

:global(.vcg6jsbkc) {
  fill: currentColor;
  d: path("M3 9H1v11c0 1.11.89 2 2 2h16v-2H3z");
}

</style>
