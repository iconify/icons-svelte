<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skqs4loul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:on-hub-device-sharp" {...props}></Icon>
<style>
:global(.skqs4loul) {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3L6.825 3h10.35L16 18z");
}

</style>
