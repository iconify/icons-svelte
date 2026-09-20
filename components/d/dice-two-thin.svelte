<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lxskuj-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dice-two-thin" {...props}></Icon>
<style>
:global(.lxskuj-aa) {
  fill: currentColor;
  d: path("M192 36H64a28 28 0 0 0-28 28v128a28 28 0 0 0 28 28h128a28 28 0 0 0 28-28V64a28 28 0 0 0-28-28m20 156a20 20 0 0 1-20 20H64a20 20 0 0 1-20-20V64a20 20 0 0 1 20-20h128a20 20 0 0 1 20 20Zm-96-84a8 8 0 1 1-8-8a8 8 0 0 1 8 8m40 40a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
