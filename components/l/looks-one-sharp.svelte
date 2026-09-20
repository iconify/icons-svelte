<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lodb0-m3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-one-sharp" {...props}></Icon>
<style>
:global(.lodb0-m3w) {
  fill: currentColor;
  d: path("M12.5 16.5h1v-9h-3v1h2zM20 20H4V4h16z");
}

</style>
