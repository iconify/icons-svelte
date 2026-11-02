<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e21kbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-fill-round" {...props}></Icon>
<style>
:global(.m8e21kbff) {
  fill: currentColor;
  d: path("M21 22H3a1 1 0 0 1 0-2h2V7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v13h2a1 1 0 0 1 0 2m-6.99-11H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
