<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtek1tuzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-store-mall-directory" {...props}></Icon>
<style>
:global(.jtek1tuzt) {
  fill: currentColor;
  d: path("M20.16 7.8c-.09-.46-.5-.8-.98-.8H4.82c-.48 0-.89.34-.98.8L3 12v1c0 .55.45 1 1 1v5c0 .55.45 1 1 1h8c.55 0 1-.45 1-1v-5h4v5c0 .55.45 1 1 1s1-.45 1-1v-5c.55 0 1-.45 1-1v-1zM12 18H6v-4h6zM5 6h14c.55 0 1-.45 1-1s-.45-1-1-1H5c-.55 0-1 .45-1 1s.45 1 1 1");
}

</style>
