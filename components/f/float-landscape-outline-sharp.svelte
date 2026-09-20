<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi-tg0bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.vi-tg0bdw) {
  fill: currentColor;
  d: path("M2 20V4h20v7h-2V6H4v12h11v2Zm15 0v-7h5v7Zm-5-8Z");
}

</style>
