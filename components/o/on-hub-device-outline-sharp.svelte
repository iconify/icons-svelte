<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md9y-bcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:on-hub-device-outline-sharp" {...props}></Icon>
<style>
:global(.md9y-bcnh) {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3L6.825 3h10.35L16 18zm1.85-2h4.3L15 5H9zm0-11H9h6z");
}

</style>
