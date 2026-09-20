<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbh9pl0-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:delete-sharp" {...props}></Icon>
<style>
:global(.fbh9pl0-x) {
  fill: currentColor;
  d: path("M9 17h2V8H9zm4 0h2V8h-2zm-8 4V6H4V4h5V3h6v1h5v2h-1v15z");
}

</style>
