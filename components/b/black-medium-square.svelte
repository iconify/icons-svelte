<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="q_2bswb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:black-medium-square" {...props}></Icon>
<style>
:global(.q_2bswb_p) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M33 30a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3z");
}

</style>
