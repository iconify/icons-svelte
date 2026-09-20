<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngjo63gsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:altitude-outline" {...props}></Icon>
<style>
:global(.ngjo63gsy) {
  fill: currentColor;
  d: path("M18 12V7.8l-1.6 1.6L15 8l4-4l4 4l-1.4 1.425l-1.6-1.6V12zM1 22l6-8l4.5 6H19l-5-6.65l-2.5 3.3L10.25 15L14 10l9 12zm10.5-2");
}

</style>
