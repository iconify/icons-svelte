<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7mc6xwix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-keyhole-fill" {...props}></Icon>
<style>
:global(.o7mc6xwix) {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0v3h2a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3Zm6-3a2 2 0 1 0-4 0v3h4Zm-3 9.733V18a1 1 0 0 0 2 0v-2.267a2.001 2.001 0 1 0-2 0");
}

</style>
