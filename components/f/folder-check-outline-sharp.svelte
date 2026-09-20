<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcqho8b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-check-outline-sharp" {...props}></Icon>
<style>
:global(.fcqho8b0l) {
  fill: currentColor;
  d: path("M10.85 16.575L16.5 10.9l-1.4-1.4l-4.25 4.25l-2.125-2.125L7.3 13.05zM2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6z");
}

</style>
