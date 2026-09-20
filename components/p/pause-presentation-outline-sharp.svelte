<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-17n8sfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pause-presentation-outline-sharp" {...props}></Icon>
<style>
:global(.m-17n8sfd) {
  fill: currentColor;
  d: path("M9 16h2V8H9zm4 0h2V8h-2zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
