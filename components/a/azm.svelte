<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6d7zcb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:azm" {...props}></Icon>
<style>
:global(.m6d7zcb1g) {
  fill: currentColor;
  d: path("m16 17l4-4V4h-9L7 8h9zm-6 6l4-4v-9H5l-4 4h9z");
}

</style>
