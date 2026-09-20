<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmbz_zbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:road-24-filled" {...props}></Icon>
<style>
:global(.wmbz_zbcr) {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 0-2 0v18a1 1 0 1 0 2 0zm14 0a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0zm-7 0a1 1 0 1 0-2 0v3a1 1 0 1 0 2 0zm-2 10.5a1 1 0 1 0 2 0v-3a1 1 0 1 0-2 0zm0 4.5a1 1 0 1 1 2 0v3a1 1 0 1 1-2 0z");
}

</style>
