<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od25a--7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:account-balance" {...props}></Icon>
<style>
:global(.od25a--7n) {
  fill: currentColor;
  d: path("M4 10h3v7H4zm6.5 0h3v7h-3zM2 19h20v3H2zm15-9h3v7h-3zm-5-9L2 6v2h20V6z");
}

</style>
